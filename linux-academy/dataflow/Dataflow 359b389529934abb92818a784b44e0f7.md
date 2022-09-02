# Dataflow

Simplified stream and batch data processing with equal reliability

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled.png)

- having two separate pipelines made it difficult to compare recent and historical (batch) data

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%201.png)

- apache beam enables you to create unified batch and data processing pipelines and cloud dataflow enables you to execute those pipelines with all the cloud advantages (such as autoscaling)

# Overview

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%202.png)

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%203.png)

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%204.png)

# Key concepts

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%205.png)

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%206.png)

# Best practices

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%207.png)

## Windowing

Some Beam transforms, such as `GroupByKey` and `Combine`, group multiple elements by a common key. Ordinarily, that grouping operation groups all of the elements that have the same key within the entire data set. With an unbounded data set, it is impossible to collect all of the elements, since new elements are constantly being added and may be infinitely many (e.g. streaming data). If you are working with unbounded `PCollection`s, windowing is especially useful.

In the Beam model, any `PCollection` (including unbounded `PCollection`s) can be subdivided into logical windows. Each element in a `PCollection` is assigned to one or more windows according to the `PCollection`'s windowing function, and each individual window contains a finite number of elements. Grouping transforms then consider each `PCollection`'s elements on a per-window basis. `GroupByKey`, for example, implicitly groups the elements of a `PCollection` by *key and window*.

**Caution:** Beam’s default windowing behavior is to assign all elements of a `PCollection` to a single, global window and discard late data, *even for unbounded `PCollection`s*. Before you use a grouping transform such as `GroupByKey` on an unbounded `PCollection`, you must do at least one of the following:

- Set a non-global windowing function. See [Setting your PCollection’s windowing function](https://beam.apache.org/documentation/programming-guide/#setting-your-pcollections-windowing-function).
- Set a non-default [trigger](https://beam.apache.org/documentation/programming-guide/#triggers). This allows the global window to emit results under other conditions, since the default windowing behavior (waiting for all data to arrive) will never occur.

If you don’t set a non-global windowing function or a non-default trigger for your unbounded `PCollection` and subsequently use a grouping transform such as `GroupByKey` or `Combine`, your pipeline will generate an error upon construction and your job will fail.

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%208.png)

The simplest form of windowing is using **fixed time windows**: given a timestamped `PCollection` which might be continuously updating, each window might capture (for example) all elements with timestamps that fall into a 30 second interval.

A fixed time window represents a consistent duration, non overlapping time interval in the data stream. Consider windows with a 30 second duration: all of the elements in your unbounded `PCollection` with timestamp values from 0:00:00 up to (but not including) 0:00:30 belong to the first window, elements with timestamp values from 0:00:30 up to (but not including) 0:01:00 belong to the second window, and so on.

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%209.png)

A **sliding time window** also represents time intervals in the data stream; however, sliding time windows can overlap. For example, each window might capture 60 seconds worth of data, but a new window starts every 30 seconds. The frequency with which sliding windows begin is called the *period*. Therefore, our example would have a window *duration* of 60 seconds and a *period* of 30 seconds.

Because multiple windows overlap, most elements in a data set will belong to more than one window. This kind of windowing is useful for taking running averages of data; using sliding time windows, you can compute a running average of the past 60 seconds’ worth of data, updated every 30 seconds, in our example.

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%2010.png)

![Untitled](Dataflow%20359b389529934abb92818a784b44e0f7/Untitled%2011.png)