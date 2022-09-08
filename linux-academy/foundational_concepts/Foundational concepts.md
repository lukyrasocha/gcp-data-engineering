# Foundational concepts

# Data lifecycle

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled.png)

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled%201.png)

cold data refers to data that is rarely accessed, therefore considered "cold". **Cold data is the opposite of hot data, which is data that is frequently accessed**

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled%202.png)

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled%203.png)

# Batch and Streaming Data

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled%204.png)

# Cloud storage as staging ground

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled%205.png)

A data lake is **a centralized repository designed to store, process, and secure large amounts of structured, semistructured, and unstructured data**
. It can store data in its native format and process any variety of it, ignoring size limits.

Not always the best choice if you are working with streaming or hot data

Usually the first option for migrating your existing workloads on cloud (importing existing databases from on premise setup onto google cloud)

Acting as a **data lake** that your other google services can pull data from

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled%206.png)

**Storage Transfer Service**

- used to get data specificially from Amazon S3 bucket , another GCS bucket, or another publicly accessible HTTP or HTTPS locations into Google Cloud
- either one time transfer or periodic sync to make sure that the source and target location are always in sync with each other

**Data Transfer Appliance**

- google will send you physical hardrive on which you upload the data and ship it back to google, they will then upload it

**Other methods**

- gsutil command

# Database types

 

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled%207.png)

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled%208.png)

# Monitoring unmanaged databases

= databases hosted on google compute engine

![Untitled](Foundational%20concepts%20f491cb49ce7e415f8d870aaedc35e16a/Untitled%209.png)

If you install for example a MySQL on a compute engine instance, you get by default some built in logging and monitoring, for example ‘Audit logs’ as ‘who created this instance?’ but you have no information about MySQL (the application itself) - that requires additional configurations