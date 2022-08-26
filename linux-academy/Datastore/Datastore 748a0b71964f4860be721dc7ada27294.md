# Datastore

# Overview

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled.png)

**No Ops**

- we don’t have to set up in advance or provision instances (their storage etc)
- you just use it (Datastore) there is no setting up in advance

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled%201.png)

# Data organisation

- key - value store

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled%202.png)

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled%203.png)

# Queries and Indexing

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled%204.png)

<aside>
💡 When you run a query, you don’t computations on the database itself to get the result, rather what happens behind the scenes is that an index is automatically created for you and when you run a query, the query runs against the index → as you add additional data to the database, the index is automatically updated to reflect those changes

</aside>

**The built in index** allows simple single property queries (there is one index (one table) for each property)

- only a single property at a time
- so if you try to have a query with filter on two properties it will return an error

**Composite index**

- specified by index configuration file
- allows you to query based on more properties at a time

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled%205.png)

`gcloud datastore indexes create index.yaml`

**Exploding indexes**

- by default you only have index on one property at a time (its not combining different sets of properties)
- but if you load a composite index, what happens is that the index needs to create every single possible combination of every single property
- to avoid them, narrow the scope in the index.yaml file, you dont have to index every single property in your entity (dont index properties that will not be used for queries)

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled%206.png)

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled%207.png)

 

# Data Consistency

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled%208.png)

![Untitled](Datastore%20748a0b71964f4860be721dc7ada27294/Untitled%209.png)