# Bigtable

# Overview

![Untitled](Bigtable%20f98aef35ae474b278b6a7d43e9fefc27/Untitled.png)

![Untitled](Bigtable%20f98aef35ae474b278b6a7d43e9fefc27/Untitled%201.png)

# Instance Configuration

![Untitled](Bigtable%20f98aef35ae474b278b6a7d43e9fefc27/Untitled%202.png)

# Data organisation

![Untitled](Bigtable%20f98aef35ae474b278b6a7d43e9fefc27/Untitled%203.png)

- Row key is the only data that is indexed, or in other words the only piece of data you can run query against within the entire big table itself. So anything that we want to make a query on needs to be in the first column or we will not be able to find it
- Field promotion - move fields from column data to row key
    - if you wish to have some columns to query against, you move them to the row key (you combine them in a single column called the row key (Lukas#rasocha.lukas@gmail.com#09.06.99)

# Schema design

![Untitled](Bigtable%20f98aef35ae474b278b6a7d43e9fefc27/Untitled%204.png)

- Reverse domain names
    - this is because due to the different combination of web adresses available you want to start with the largest scope (.com) then go to linuxacademy and then support, essentially going from the biggest qualifier to the lowest
- if you have some identifier as a username, you want to add that identifier as a portion of the row key as well
- when working with timestamps, it is also good to include them, but also REVERSE them so going from big to small (same as the domain names) and not use them at front! - either middle or the end)

Hotspotting happens when you have a rowkey with a very specific term at the start of the row key (low scope) and that is BAD (such as non-reversed timestamp)

- Sequential IDs can also lead to hotspotting and that is because due to the method that BigTable uses to query the results, it could again push all the different requests in traffic to a small number of nodes which could lead to hotspotting as well

Sequential numeric IDs will read and write from the same node, causing increased load.

Like sequential IDs, timestamps will read and write from the same node, causing increased load.