# Cloud Spanner

# Overview

![Untitled](Cloud%20Spanner%207a70fdbf17a54d28a364dbc8768d1add/Untitled.png)

![Untitled](Cloud%20Spanner%207a70fdbf17a54d28a364dbc8768d1add/Untitled%201.png)

![Untitled](Cloud%20Spanner%207a70fdbf17a54d28a364dbc8768d1add/Untitled%202.png)

Nodes handle computation for queries, similar to that of BigTable

Each node serves up to 2 TB of storage

More nodes = more CPU/RAM = increased throughput

Storage is replicated across zones (or regions if you are using a multi-regional setup). Like Bigtable, storage is separate from computing nodes

The update however differs from Bigtable in a way, that if you make a write to a Bigtable you will eventually get all the replicas contain the same values, but with Spanner whenever an update is made to a database in one zone/region, it is automatically replicated across zones/regions

- Automatic synchronous replication
    - when data is written, you know it is been written
    - any reads guarantee data accuracy

![Untitled](Cloud%20Spanner%207a70fdbf17a54d28a364dbc8768d1add/Untitled%203.png)

# Data Organization and Schema

![Untitled](Cloud%20Spanner%207a70fdbf17a54d28a364dbc8768d1add/Untitled%204.png)

![Untitled](Cloud%20Spanner%207a70fdbf17a54d28a364dbc8768d1add/Untitled%205.png)

Sequential numeric IDs will read and write from the same node, causing increased load.

Like sequential IDs, timestamps will read and write from the same node, causing increased load.

in a classical MySQL database, if you have two sets of tables that are related, you would query them with join function

in Spanner you have the chance to define whats called a Child Parent relationship between two or more tables (for efficient retrieval) - you can think of it as if one table was nested in its parent table

- for this to work you need to set up primary keys that tell which child goes with what parent table

**Example**

- parent table called singers
- child table called albums
- and then a child table to the album table called Songs

To avoid hotspotting, dont use sequential numbers!