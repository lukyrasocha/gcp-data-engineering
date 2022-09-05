# Dataproc

**Dataproc** is a managed Spark and Hadoop service that lets you take advantage of open source data tools for batch processing, querying, streaming, and machine learning

![Untitled](Dataproc%20324fe141ccb34a09887c33065c73abae/Untitled.png)

- With Dataproc you need to manage only Custom Code

# MapReduce

- take big data, distribute it to many workers (map)
- combine results of many pieces (reduce)
- Distributed (parallel) computing

![Untitled](Dataproc%20324fe141ccb34a09887c33065c73abae/Untitled%201.png)

# Pricing

![Untitled](Dataproc%20324fe141ccb34a09887c33065c73abae/Untitled%202.png)

![Untitled](Dataproc%20324fe141ccb34a09887c33065c73abae/Untitled%203.png)

To interact with dataproc cluster via the web interface you should use SOCKS Proxy

# Migrating to GCP

**What are we moving/optimizing**

- Data (from HDFS)
- Jobs (Pointing to google cloud locations)
- Treating clusters as ephemeral (temporary) rather than permanent entities

![Untitled](Dataproc%20324fe141ccb34a09887c33065c73abae/Untitled%204.png)

![Untitled](Dataproc%20324fe141ccb34a09887c33065c73abae/Untitled%205.png)

![Untitled](Dataproc%20324fe141ccb34a09887c33065c73abae/Untitled%206.png)

# Lift and Leverage instead of Lift and Shift

- we move to the cloud but try to optimise for it as well
- instead of keeping all the data in the cluster, we seperate the storage from the compute, so then we can delete the cluster (and all its costs) when we no longer need to compute (when the job has finished)
- when we have a cluster on premises, we usually think of it as a pernament thing, whereas on a cloud it is ephemeral

![Untitled](Dataproc%20324fe141ccb34a09887c33065c73abae/Untitled%207.png)

![Untitled](Dataproc%20324fe141ccb34a09887c33065c73abae/Untitled%208.png)