# Blogs

# Blog 1

- Pub/Sub => Apache Kafka
- Dataflow => Apache Beam
- Dataproc => Apache Hadoop
- Composer => Apache Airflow
- BigQuery => Apache Hive
- ML Engine / AI Platform => Apache SparkML
- Bigtable => Apache HBase
- noSQL databases such as Bigtable or Datastore => MongoDB, Cassandra
- SQL databases such as Cloud SQL or Spanner => MariaDB
- Dataprep => Trifacta

## **Going for the Data Engineer: How to prepare**

Similar to the Architect preparation, I used a mix of Coursera, Cloud Guru (former Linux Academy), Google Cloud’s documentation and Whizlabs. With Coursera, I studied the following four courses:

1. Google Cloud Platform Big Data and Machine Learning Fundamentals
2. Modernizing Data Lakes and Data Warehouses with GCP
3. Building Batch Data Pipelines on GCP
4. Building Resilient Streaming Analytics Systems on GCP

Do all the practice exams and focus on things you didnt understand, find them in the official documentation

Plenty of questions centered on how to best choose between Google Cloud and its open-source alternatives. It also felt like access control (e.g. IAM) and security and monitoring measures (e.g. authorized views, Stackdriver and CMEK/CSEK) had a significant share in the overall picture. AutoML versus Vision API showed up at least twice, so this is something that one should be able to easily distinguish.

# Blog 2

Here are some of the **key products that are covered**:

Cloud Storage, BigQuery incl BigQuery ML and Data Studio, Dataflow, Dataproc, Pub/Sub, Composer, Datafusion, Kubeflow, ML APIs, AutoML, AI notebooks.

I recommend checking out the following **3 courses** from the specialisation:

- [Big data and ML fundamentals](https://www.coursera.org/learn/gcp-big-data-ml-fundamentals?specialization=gcp-data-machine-learning)
- [Data lakes and data warehouses](https://www.coursera.org/learn/data-lakes-data-warehouses-gcp?specialization=gcp-data-machine-learning)
- [Smart analytics, ML and AI on GCP](https://www.coursera.org/learn/smart-analytics-machine-learning-ai-gcp)

# Blog 3

1. **Go through the exam guide**

You will first have to go through the exam guide given on the official exam page. Once you have gone through that, you will notice that there are 4 modules included in the guide. The guide is structured in a way where you first learn about designing a pipeine, operationalising it, how to incorporate GCP’s ML capabilities, and at last, making your solution scalable and fault tolerant. So, I would suggest that you start studying in the same order as they are given in the guide.

[Exam Guide](https://cloud.google.com/certification/guides/data-engineer)

2. **Take an online course**

As a first step in my preparation I went through an online course available on Coursera. There are other options also available like linux academy or udemy. Even on Coursera, there are multiple courses for the same exam and some of them also include hands on practice labs

a. Coursera : [Preparing for the Google Cloud Professional Data Engineer Exam](https://www.coursera.org/learn/preparing-cloud-professional-data-engineer-exam) (course)

b. Coursera : [Data Engineering, Big Data, and Machine Learning on GCP](https://www.coursera.org/specializations/gcp-data-machine-learning) (Specialization consisting of 5 courses)

c. Linux Academy : [Google Cloud Certified Professional Data Engineer](https://linuxacademy.com/course/google-cloud-data-engineer/) (course)

d. Udemy : [Google Cloud Professional Data Engineer Course [2019 Update]](https://www.udemy.com/course/learn-gcp-become-a-certified-data-engineer-express-course/) (course)

I personally went ahead with option (a) as I had a time constraint and it was really good. The option (b) is a pack of 5 courses which helps you develop a deeper understanding of all the services and you can choose to go that way if you have ample amount of time in your hands.

The Linux Academy course basically covers on the things required from an exam point of view. So, I would rate it a little bit lower than the Coursera ones.

I do not have any experience with the Udemy course but, it should be good enough. At least that is what I have heard from my colleagues.

There are certain things you should keep in mind whilst going through these courses. Always sit with a notepad or something on which you can make your notes as and when the course proceeds. Segregate your notes as per different services and pay attention to which services work well together and which do not. Make sure you leave one page blank after each service(you will come to know the reason later for this). Once you have started with the course, I will suggest that you complete the whole course and then move on to the documentation. you can always refer to the documentation for some small doubts, but refrain yourself from going in detail at this moment.

3. **Go through documentation**

Now that you have completed a course, you have developed a basics of all the concepts and services included in the exam and are all set to understand each and every service in depth. When going through the documentation, make sure you first start with the Concepts section for each of the service and then go through each of the links embedded in the page. Now, you would want to avoid from deviating of your topic, so make sure you only go one level deep. Meaning, go through the links mentioned in the concepts page but then don’t start going through the links in the other pages too and then the one succeeding it. Just one level down.

While going through the documentation, you will find a lot of new details that will come up. These are the things that will help to differ one service from another one. Make sure you capture all the minute details and merge them with your previous notes where we left one page. As soon as you have finished the documentation for one service, make sure you go through all the points that you have noted till now from the video and the documentation.

Going through the documentation is going to be the longest and the most important step in your preparation. So make sure you give it as much time as possible.

4. **Give a Practice Test and Review Your Feedback**

At this point, you should be comfortable with all the services and the use case in which they fit. You can go ahead and appear for the mock exam that is available on the official google page

[Mock Exam link](https://cloud.google.com/certification/practice-exam/data-engineer)

FYI : The setup is no where near the original exam. Its basically just a google form where you select you answer and move on to the next page, but the questions are going to be really really tough and lengthy.

It will be a 20 questions test and it actually doesn’t matter how much you score. I scored a 5/20, so you can imagine. The real thing that you get after appearing for this exam is the detailed feedback for each and every question.

I would suggest you to copy paste the whole thing in to a document or something so that you can refer it anytime you want. This thing is literally gold for preparation. This review will not only tell which one is the right answer but also that why are other choices wrong.

First of all, you want to go through all the questions and the provided explanations for them. And you should spend at least 1 complete hour for reviewing these 20 questions. With each explanation, you will find a document link attached below it. What you want to do is make a list of these links in a separate place and and then categorize them as per services so that when you start with a section you can go through all of the ones related to it.

I have also attached the the [list](https://docs.google.com/document/d/1qMk5ksS0yAa9qwXZs7E3pc1MMhqHNivpkdf1H5Bf7cs/edit?usp=sharing) of links that I collated from my Mock Exam

5. **Mock Exams and Review**

This not the exam that we took in the previous step. Here I am talking about an exam which is on par with the actual exam in terms of the screen you use and the level of questions that are asked in the real exam. I would suggest going and buying one of the Mock Exams available on Udemy.

The one that I bought is no longer available, but there are other options that you can select from and they are really cheap, when you compare it with the exam cost. The below link will have different options, but make sure that you select the one which has at least 2 practice tests with 50 questions present in each of them. This will also help you to focus for a 50 questions long test.

[Udemy Mock Tests](https://www.udemy.com/courses/search/?src=ukw&q=GCP+data+engineer+mock+exam)

Make sure you take the test in an isolated environment and spend more time on reviewing the test. It is of utmost importance that you review each and every question of the test. Irrespective of wrong or right. You need to go through all of them and create a separate list where in you note down the points which are new for you or that you might think are important. Also, this reviewing process needs to be done as soon as you finish the exam. This will make sure that the reasons that came to your mind while selecting a particular option are still there and you will be able to crosscheck whether they were right or wrong.

In my case, I use to get over with the test in around 1 hour and then it would take me around 2 hours to review all the questions and note the important points.

**THE MOST IMPORTANT PART**

**Now before you appear for an other test you want to go through all the notes that you have made before from the videos and documentation and also the points that you have noted down from all your previous exams**

This should hardly take an hour. Remember I am not asking you to by heart everything that you have written. I am just asking you to read through it as many times as possible.

You should continue this practice until you have finished all your tests. Now, if you still have some days left before your exam, I would suggest going through the whole set of all the notes that you have prepared **at least** twice a day. Also you can appear for the exams that you have bought from Udemy as many times as you want, so you can appear for them again too

# Blog 4

### Topics in the certification exam

The section provides a list of the main topics covered in the exam, some sub-topics, and occasionally my thoughts about the material.

**BigQuery (A major focus in the exam)**

- Integration with Google Identity and Access Management (IAM) roles
- Basic understanding of the GCP Key Management Sevice (KMS) and keys (google-managed, customer-supplied, and customer-managed)
- Partitioned tables, specifically as used in SQL commands
- Wildcards
- Federated tables
- Integration with Google Cloud Storage (GCS)
- BigQuery (BQ) data transfer service and connectors
- When to use normalized and denormalized data
- Loading different data formats into BQ, including a good understanding of the Apache Avro™, CSV, Apache Parquet, and JSON formats
- Pricing with slots
- Cached queries

**Dataflow**

- Integration with IAM roles, especially the developer role
- Differences between global, fixed, session, and sliding windows and when to use each type
- Best practices on handling pipeline errors, especially, try-catch-block errors
- Different types of transform methods, for example, Apache Beam ParDo
- Watermarks
- Apache Beam

**BigTable**

- Schema design, such as when to use tall and narrow tables or short and wide ones
- Schema that might cause slow performance and how to optimize performance
- When to use hard disk drive (HDD)
- How to switch between HDD and solid-state drive (SSD)

**Pub/sub**

- Process of moving from the Apache Kafka to pub/sub workflow
- IAM controls on different levels, such as the fact that the publisher level has no IAM controls
- Learn how the process of message flow works, such as why delays in sending messages might occur

**Cloud Spanner**

- Not much in the exam, just basic concepts
- Primary and secondary indexes

**Dataproc**

- Good understanding of the Apache Hadoop ecosystem
- IAM integration
- Benefits of preemptible nodes
- Best practices for migrating Hadoop clusters to Dataproc, such as always separating data from storage by using GCS
- Best practices for optimizing performance
- Connectors
- Apache Spark

**Dataprep**

- Not much in the exam but you should know the basic concepts

**Machine Learning**

- Differences between training and test data.
- Overfitting and underfitting, such as why they can happen, how to prevent them.
- Good understanding of ML types, including supervised learning, unsupervised learning, reinforcement learning, although I saw no questions on reinforcement.
- Not much on Tensorflow, but you should know the basic concepts.
- Good understanding of how neural networks (NN) work. There were questions on wide NN, deep NN, and both wide and deep NN.
- Regularization parameters, such as L1 and L2, including a couple of scenario-based questions of when to use each type.

**GCP ML services**

- Good understanding of each service, especially Natural Language API, such as sentiment and entity analysis
- A couple of questions on when it is beneficial for a customer to use ML services
- AI platform, including how it works and online versus batch predictions

**Datalab**

- Basic concepts
- A question came up about how you can share notebooks

**DataStudio**

- Basic concepts
- Caching with BQ, including query cache and prefetch cache
- A question came up about metrics and dimensions, so you should know the difference

**Cloud Composer**

- You should know directed acyclic graph (DAG) files in detail, including the components.

**Extra notes**

- The exam had no case studies.
- The exam didn’t have much on Cloud SQL.
- You should know the data pipelines very well.
- You should know the key differences between the data services in GCP.
- The **[Google practice exam](https://cloud.google.com/certification/practice-exam/data-engineer)** is also quite useful, so consider taking it.

# Blog 5

Most part of my exam were focused in ETL problems, So all the optimizations techniques and best practices with, Dataproc, Pubsub, Dataprep, Dataflow, and Bigquery is essential. Another focused part were differentiate between Cloud Composer, Scheduler and Cron jobs. Last but not least, heavily technical questions for Bigquery optimization with partitioning, slots management and clustering techniques.

But I definitely would study more about the different applications for Cloud Composer vs Scheduler vs cron job in different jobs kind. Of course I know in a big data/ETL scenario I would prefer Cloud composer. I would study more IAM best practices to be confident with my answers and TPU vs GPU implementation in code (I have some experience in launch TPU environments but the specific question in the exam got me).

# Blog 6

## **Machine Learning**

The exam (questions are random so I don’t know about other experience) was really heavy on Machine Learning topics. There was like 15 question about this. Mostly related to:

- Overfit models
- How to deal with high RMSE, for example: make your model more complex and robust.
- Neurons, features, epoch, labels.
- L1 and L2 regularization
- Dialogflow
- Cloud AutoML to label some logos within an image.
- Cloud Vision API, Speech to Text, etc.
- Tensorflow models in C++
- Cloud TPU and GPU

## **BigQuery**

The exam was heavy on BigQuery questions too. Questions related to Updates on Bigquery, IAM roles, Slots, Storage, etc.

- Update DML: How to use Update DML in BigQuery, how you can handle quota error exceded in your project. How many simultaneous updates can you run on a daily basis? Best ways to update a table (for example, if you have a partitioned table, etc.).
- Authorized View: I recommend studying all about authorized views, how you can share queries to your data science team without the necessity of query the entire columns of a table.
- Allocated Slots and Available Slots: What can you do if you don’t have more slots available and you don’t want to create a new project in your organization?
- Storage: Questions related to the best way to store raw data, for example between BigQuery or Storage. This will depend on the context of the question and if price or performance is the priority.
- BigQuery Data Transfer Service and the connection available with BI tools.
- Partition and clustering
- HASH, Merge, Data manipulation. 2 questions related to this.

## **BigTable**

I have no professional experience working with BigTable so the knowledge that I have was mostly theoretical.

- There were 2 questions related to Row key performance and how you can update your cluster if the performance is not optimal due to high reads or write.
- How you can scale your cluster and synchronize the data.
- Single-cluster routing and multi-cluster routing.
- Key Visualizer Metrics

## **Spanner**

Knowing about *default indexes* and *secondary indexes* is a must and when to choose Spanner over Datastore, Bigtable, or CloudSQL.

- Regional configuration and replicas.
- Monitoring CPU

## **CloudSQL**

I remember just one question about CloudSQL. I recommend knowing how to export data from CloudSQL to BigQuery, on-premises databases to CloudSQL, Cloud SQL HA, and read replicas.

## **Datastore**

Again, the key here is when to choose DataStore over other databases like CloudSQL, BigTable, BigQuery, etc.

- How you can export data from DataStore to BigQuery.
- Replicas between other projects.
- Multiple indexes and syntax to create composite indexes are going to be really helpful.

## **Dataflow**

This topic was really technical and if you don’t have experience working with Dataflow it may be a little bit tricky.

- How to discard erroneous data and for example sent it to Pub/Sub or Cloud Storage
- Transform, DoFn, Sideinputs, Sideoutputs.
- IAM Roles for Developers and how to secure the data.
- Windows, all kinds of them. There were 3 questions about Sliding time windows, Session time windows, the best way to deal with late data.
- Bounded and unbounded data.
- How to connect with Pub/Sub, BigQuery, BigTable, etc.

## **Pub/Sub**

I recommend understanding the difference between push and pull and what you need to implement a push solution.

This service is glue with other Cloud components so there was some question related to Pub/Sub / Dataflow / BigQuery implementation.

- Streaming and how to implement this solution with Dataflow
- Globally Unique Identifier (GUID)
- Handle subscriber code errors
- How to connect Kafka to Pub/Sub
- How to know when your topic is currently not working well. This is mostly related to Stackdriver Monitoring.

## **Dataproc**

This was pretty heavy on on-prem Hadoop implementations and how to migrate to GCP.

- Migrate jobs to the cloud.
- Which role needs the service account to work properly with Dataproc (Dataproc Worker).
- SOCKS and YARN for web Interface.
- Custom images.
- Use Storage instead of HDFS.
- Always remember that Google recommends one cluster for one task. If you need analytics and transactional solutions with Dataproc, it’s better to create two clusters for that kind of implementation.

## **IAM Roles**

It’s going to be useful to know the most important roles for every Service

- Different between jobUser role and User for BigQuery.
- Dataproc Worker, Dataflow Developer.
- Billing Administrator Role Account.
- Difference between Writer and Reader role for BigQuery.
- Which roles can you administrate for Pub/Sub service?
- Aggregated logs for multiple projects.
- Dealing with roles cross projects, what are the best practice for that, create a group of users for those projects? hierarchy? Service Accounts for Cloud Storage and BigQuery?

## **Cloud Storage**

Here, it’s a must to know the differences between every class in Storage. The exam questions were really tricky between cold line and nearline implementations.

- Most questions were related to how to secure raw data for audit.
- Data Transfer vs Storage transfer service.
- How you can stay in sync with on-prem storage if the on-prem storage doesn't allow any other IP from outside?

## **Composer**

This cloud component is quite easy to figure out. Remember that the Cloud Composer environment runs Airflow and Airflow itself is an Orchestrator tool. So when you want to integrate some Dataflow jobs with Dataproc jobs and there’s a dependency on each other. Always the best solution is going to be Cloud Composer.

## **DataStudio**

Study the difference between Viewer credentials and Owner credentials if you want to share some dashboards.

- Default caching and prefetch caching.
- How to connect BigQuery with DataStudio and other services like Youtube.

## **Dataprep**

There was some question related to Dataprep, for example, if you want a quite easy implementation to deal with outliers what’s the best tool for that? transform recipes, and finally, how to schedule a Dataprep implementation, do you need Cloud Scheduler for that or you can do it directly from the Dataprep UI?

## **Tips**

Besides all the key points mentioned. I found this exam heavily focused on Machine Learning, so I recommend learning all the most important vocabulary for that, like labels, epoch, neurons, hidden layers, bias, weight, learn when to implement a linear regression model instead of classification or clustering.

It’s always good to read the documentation and stay updated on every new feature added to these Cloud Services, for example, at the moment you can deploy TensorFlow, Scikit-learn, and XGBoost models to AI Platform but who knows what’s going to be in the future, the same can be applied to Machine Learning models for BigQuery.

Another good key point is to know about Stackdriver Monitor, Stackdriver Logging, Stackdriver Logging Agent, etc. I remember that there was a question about installing the Stackdriver Logging agent for a MariaDB on Compute Engine, so, that can be helpful too.

## **Courses**

**[Coursera](https://www.coursera.org/specializations/gcp-data-machine-learning)** - 5/10: If you don't have experience with GCP, start with this course. It’s a really good introduction to GCP but IMO doesn't prepare you for the exam.

**[Linux Academy](https://linuxacademy.com/course/google-cloud-data-engineer/)** - 7/10: This course is focused to prepare you for the exam but it doesn't go too deep into every service related to the exam, still, it’s a must IMO to take this course and then read the documentation.

**Documentation** - 8/10: The official documentation really helped me to go deeper into some topics, like clustering configuration for BigTable, Machine Learning models for BigQuery, Dataproc, Dataflow, etc. I recommend giving you time to read the documentation because is quite heavy and it’s going to take a while but the compensation for that is big.

## **Practice exams**

**[BrainCert](https://www.braincert.com/course/16716-Google-Cloud-Certified-Professional-Data-Engineer-Practice-Exams)** - 8/10: I would say this practice exams course is the best out there. The questions really prepare you for the real exam and you are going to gain more knowledge after reading the explanation for each answer and question. I did two tests almost every day for about 2 weeks until reaching between 94-100% for every test.

I hope that this post will be helpful for all of you that are going to take the exam in the future. Please let me know if you have any questions!

# Blog 6

## **Lift and Shift vs Lift and Leverage**

If you’ve watched some of the online courses, you may recognise these terms.

**Lift and Shift** is simply migrating existing processes or infrastructure to the cloud without redesigning anything. Some companies might take this approach because they don’t want to spend time and money modifying their current infrastructure but still want to use the benefits of the cloud. For example, hosting a MySQL database on compute engines rather than migrating all the data to Cloud SQL.

**Lift and Leverage** means to move your existing processes over to the cloud and make them better using some of the services the cloud has to offer. For example, you can use Dataproc to run your Hadoop and Spark workloads but store the data in Cloud Storage as opposed to storing it in HDFS. This is more cost-efficient since you only pay for the time the job is running and then you can shut down the cluster when you aren’t using it without losing all its data since it is now stored in Cloud Storage.

After doing all the online courses and the practice questions, you might think that most of the answers involve choosing the most appropriate Google Cloud service for a particular business or technical requirement. After all, Google is selling their superior, low-cost, fully managed, no-ops capabilities of its Cloud Services.

However, this is not always the case and it’s important to read the question carefully as some questions in the exam have a technical requirement where they don’t want to make any modifications to their existing processes.

## **Cost vs Performance**

The hardest part of the exam for me was the trade-off between cost and performance. (This is probably where your 3+ years of industry experience might come in handy!). The business people think in terms of minimising costs and the technical people think in terms of increasing performance.

A common question is phrased along the lines of ‘A mid-size company wants to [do something] whilst keeping costs low’. While some situations are obvious such as using Cloud SQL vs Cloud Spanner, scenarios which involve running jobs are harder since you could use more powerful CPU’s (which costs more) to run a job, resulting in a shorter runtime (costs less).

## **Some other areas you should look at**

**BigQuery ML —** Recently, there’s a trend to make AI accessible to everyone. BigQuery ML allows users to create and execute machine learning models in BigQuery using standard SQL queries as opposed to writing code. One of the big advantages is that the data does not leave BigQuery. Check out this [video](https://www.youtube.com/watch?v=6Kska20zQO4) for a simple explanation.

**Kafka —** I read from other sources that Kafka appears a lot in the exam and it was true in my case as well. The Google Cloud equivalent is Cloud Pub/Sub. You should be aware of the differences between the two such as Pub/Sub only holds data for up to seven days whereas Kafka can store as much data as you want and can be accessed anytime.

**Failover replica —** As stated in syllabus 4.3 of the exam guide, it is important to think about a backup solution for your data infrastructure. Some Google Cloud services create copies of the data automatically, whereas others have to be set up manually. Think about which regions and zones you want to provision services. What happens if a data centre in a zone goes down? How do you prepare for this?

**Cloud Key Management & Data Encryption —** Data security is a very important component of data engineering. By default, GCP encrypts all customer data at rest. You should be aware that there are other encryption methods including CMEK, CSEK and Client-Side Encryption. Google Cloud has a Cloud Key Management Service that lets you manage cryptographic keys for your cloud services.

![https://miro.medium.com/max/700/1*o3wCenvbnL0SpUy0_a3hFw.png](https://miro.medium.com/max/700/1*o3wCenvbnL0SpUy0_a3hFw.png)

Table comparison of different data encryption types (Coursera)

# **Studying strategy**

Everyone has a different studying technique so you should find one that suits your lifestyle. I’m not suggesting that you adopt my approach, but if you haven’t found your style or have found that other techniques don’t work, feel free to try mine.

## **Foundational Knowledge**

In terms of online courses, I recommend the following order.

1. **Linux Academy** — *[Big Data Essentials](https://linuxacademy.com/cp/modules/view/id/74?redirect_uri=https://app.linuxacademy.com/search?query=Big%20Data%20Essentials) (optional) —* A non-technical introduction to the world of Big Data with a high-level description of the Hadoop ecosystem.
2. **Linux Academy** — *[SQL Primer](https://linuxacademy.com/cp/modules/view/id/52) (optional) —* An introduction to SQL. You will need some basic SQL knowledge for BigQuery.
3. **Linux Academy** — *[Google Cloud Certified Professional Data Engineer](https://linuxacademy.com/course/google-cloud-data-engineer/) —* An in-depth introduction to the main GCP services you can expect to see in the exam.
4. **Coursera —** *[Data Engineering with GCP Professional Certificate](https://click.linksynergy.com/deeplink?id=y5ucJvNe81w&mid=40328&murl=https%3A%2F%2Fwww.coursera.org%2Fprofessional-certificates%2Fgcp-data-engineering) —* Slightly more advanced, and focuses more on the role of a data engineer in the real world.
5. **Cloud Academy —** *[Google Data Engineer Exam — Professional Certification Preparation](https://cloudacademy.com/learning-paths/data-engineer-professional-certification-preparation-for-google-83/) —* Good to use as a refresher closer to the exam date. Spend some time looking at the topics that aren’t covered in other online courses.
6. **[Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/ml-intro) —** Covers the maths and motivation behind the most commonly used algorithms in data science. For the exam, you should know which algorithm is appropriate for the business requirement including supervised (regression, classification), unsupervised (clustering) and reinforcement learning.
7. **Coursera *—** [Preparing for the Google Cloud Professional Data Engineer Exam](https://click.linksynergy.com/deeplink?id=y5ucJvNe81w&mid=40328&murl=https%3A%2F%2Fwww.coursera.org%2Flearn%2Fpreparing-cloud-professional-data-engineer-exam) —* This is actually part of the Coursera course mentioned above but I recommend taking this a week or two before the exam. This course covers all the points in the official exam guide.

## **Hands-on practice**

If you don’t have a lot of experience using the Google Cloud Platform, I recommend you practise using the hands-on labs and Qwiklabs. You shouldn’t memorise how to do each task, but use it as an opportunity to familiarise yourself with the service and the overall GCP environment.

If you get the Linux Academy subscription, you get access to the cloud sandbox where you can receive guest user credentials to use GCP for 3 hours per session.

You can still gain valuable practice without breaking your wallet by using this cloud sandbox or by creating a free GCP account ($300 free credits) and following the task instructions for the hands-on labs on Coursera or Qwiklabs. (On Qwiklabs, you are essentially paying to use the GCP environment for a fixed time)

## **Past Papers**

My studying strategy in university was to do the past-papers as early as possible and familiarise myself with the exam style and the types of questions I can expect to see in the final exam. This way, you can spot gaps in your knowledge and focus on your weaker areas.

If you already have industry experience, I recommend this approach. If it’s your first time learning about data engineering, I recommend completing the Linux Academy course, do at least one practice exam and then move onto the Coursera course.

A month before the real exam, I did one practice exam a week. I used the Linux Academy practice exam, the Coursera practice exam and [Google’s official Data Engineer practice exam](https://cloud.google.com/certification/practice-exam/data-engineer).

The most important part of the practice paper step of your revision is to make a note of all the questions you got wrong and review them again. Once you view the answers (after taking the tests on the online courses), you will see a brief explanation of why your answer was right or wrong (and sometimes a link to the video where the topic was covered). For Google’s official practice exam, they’ll also give you links to their official documentation on the GCP website.

Here are some extra free practice questions:

- [https://www.whizlabs.com/google-cloud-certified-professional-data-engineer/](https://www.whizlabs.com/google-cloud-certified-professional-data-engineer/)
- [https://www.examtopics.com/exams/google/professional-data-engineer/view/1/](https://www.examtopics.com/exams/google/professional-data-engineer/view/1/)

I cannot stress how important it is to keep doing practice questions. Although they do not reflect the same difficulty as the real exam, you will gain exposure to a wide variety of questions and increase your confidence walking into the real exam.

## **Finally**

The course instructors **strongly emphasise** that doing the online course only is not enough to pass the exam. Your preparation should include a variety of online resources, hands-on practice with GCP and past exam questions.

There are two more things that I also included in my revision that I highly recommend.

1. **[Read the official Google Cloud Documentation](https://cloud.google.com/docs/) —** It’s unrealistic to read the whole documentation but my recommendation is to read the documentation for the topics covered in the online videos. The points you should remember are Google’s Best Practices (for doing certain things) and the quotas and limits for the some of the services (e.g. store up to 3TB of data for Cloud SQL). The rule of thumb is that if you are likely to look it up on the job (e.g. how much does 2vCPU compute engine cost per month) you don’t need to memorise it. However, you should roughly know, the upper limit for different storage types.
2. **Go through the case studies —** They used to be a part of the exam before March 2019 but are not in the current syllabus. Having said that, I found it very useful to go through these case studies. As a student without any prior data engineering experience, it was helpful to see the real-life applications and the thought process data engineers go through to come up with a technical solution to a business requirement. You can view and go through these case studies on *[Preparing for the Google Cloud Professional Data Engineer Exam](https://click.linksynergy.com/deeplink?id=y5ucJvNe81w&mid=40328&murl=https%3A%2F%2Fwww.coursera.org%2Flearn%2Fpreparing-cloud-professional-data-engineer-exam)* course on Coursera. You can watch a group of experienced professionals discuss a few potential solutions to one of the case studies [here](https://www.youtube.com/watch?v=r_yYDysfB-k&t=2238s&pbjreload=10).

# **During the exam**

The exam consists of 50 questions and you have 2 hours to finish it. There is a bookmark feature where you can bookmark questions for later review. From what I’ve read online, most people took about 1 to 1 hour 15 minutes to complete the test. I used the full 2 hours.

I would say that the exam is about 20% times harder than the practice exam. Many of the questions can inflict a lot of self-doubts such as the cost vs performance trade-off. My tip is to pace yourself and don’t waste too much time on a single question. If you don’t know the answer or are unsure about your answer, bookmark it and move on to the next.

Don’t panic if you can’t answer all the questions the first time. I got stumped on the first 5 questions and then bookmarked more than half of the questions for later review.

# Blog 7

- BigQuery Data Transfer Service. *I knew of storage transfer service and big query connectors, but I went ‘huh?’ when I saw this.*[https://cloud.google.com/bigquery/transfer/](https://cloud.google.com/bigquery/transfer/) (Edit: at the time that I wrote the exam, this was new for me. Now, it’s capabilities have also expanded.)
- IAM + Dataflow. Dataflow developer mode.[https://cloud.google.com/dataflow/docs/concepts/access-control](https://cloud.google.com/dataflow/docs/concepts/access-control)
- I̵A̵M̵ ̵+̵ ̵B̵i̵g̵Q̵u̵e̵r̵y̵.̵ ̵A̵c̵c̵e̵s̵s̵ ̵l̵e̵v̵e̵l̵ ̵v̵i̵a̵ ̵t̵a̵b̵l̵e̵s̵/̵d̵a̵t̵a̵s̵e̵t̵s̵.̵ ̵R̵e̵m̵e̵m̵b̵e̵r̵ ̵t̵h̵a̵t̵ ̵y̵o̵u̵ ̵c̵a̵n̵n̵o̵t̵ ̵r̵e̵s̵t̵r̵i̵c̵t̵ ̵a̵c̵c̵e̵s̵s̵ ̵a̵t̵ ̵t̵a̵b̵l̵e̵ ̵l̵e̵v̵e̵l̵.̵ ̵I̵t̵ ̵i̵s̵ ̵o̵n̵l̵y̵ ̵a̵t̵ ̵d̵a̵t̵a̵s̵e̵t̵ ̵l̵e̵v̵e̵l̵.̵ ̵A̵l̵s̵o̵ ̵l̵o̵o̵k̵ ̵u̵p̵ ̵w̵h̵a̵t̵ ̵A̵u̵t̵h̵o̵r̵i̵z̵e̵d̵ ̵V̵i̵e̵w̵s̵ ̵a̵r̵e̵.̵[https://cloud.google.com/bigquery/docs/access-control](https://cloud.google.com/bigquery/docs/access-control)
- *Edit 2020/06:* IAM + BigQuery. Access level. As Nikhil pointed out in the comments, you can now restrict access at Table level.[https://cloud.google.com/blog/products/data-analytics/introducing-table-level-access-controls-in-bigquery](https://cloud.google.com/blog/products/data-analytics/introducing-table-level-access-controls-in-bigquery)
- BigQuery: partitioning tables. *Based on what are they partitioned — ingestion time, timestamp, date. How are they named? How are they then accessed in queries? Using _PARTITIONTIME.*[https://cloud.google.com/bigquery/docs/partitioned-tables](https://cloud.google.com/bigquery/docs/partitioned-tables)
- BigQuery. Syntax for wildcards in big query names. *And in legacy SQL?*[https://cloud.google.com/bigquery/docs/querying-wildcard-tables](https://cloud.google.com/bigquery/docs/querying-wildcard-tables)
- BigQuery: table date range for bq. *Accessing tables with dates and partitioned tables with functions like TABLE_DATE_RANGE, _TABLE_SUFFIX, TABLE_QUERY.*[https://stackoverflow.com/questions/22641894/bigquery-wildcard-using-table-date-range](https://stackoverflow.com/questions/22641894/bigquery-wildcard-using-table-date-range)
- Cloud Spanner: secondary index for cloud spanner. *How indexes are created for you and how you can create secondary indexes.*[https://cloud.google.com/spanner/docs/secondary-indexes](https://cloud.google.com/spanner/docs/secondary-indexes)
- Datastore: multiple indexes for datastore. *Default indexes. Syntax for creating custom, composite indexes.*[https://cloud.google.com/datastore/docs/concepts/indexes](https://cloud.google.com/datastore/docs/concepts/indexes)
- BigTable: row key scheme. *What are the recommended ways for creating the row key? How do you avoid hotspotting? Should you use timestamp, and where?*[https://cloud.google.com/bigtable/docs/schema-design](https://cloud.google.com/bigtable/docs/schema-design)
- BigTable: ways to optimize.[https://cloud.google.com/bigtable/docs/performance](https://cloud.google.com/bigtable/docs/performance)
- PubSub, Dataflow, Dataproc — properties and uses of these products. The courses from Coursera, Linux Academy, and Cloud Academy cover these well.
- Dataproc: usage of gcs instead of existing file system. *It is a best practice to use Google Cloud Storage instead of using HDFS. You can destroy the compute nodes after data crunching and save cost on them.*
- BigQuery+DataStudio — caching/pre-fetch cache. *Learn how you connect DataStudio to storage solutions. Learn the difference between default caching (which cannot be disabled) and pre-fetch caching (which can be disabled). What is the difference between doing that with Viewer credentials and Owner credentials.*[https://support.google.com/datastudio/answer/7020039?hl=en](https://support.google.com/datastudio/answer/7020039?hl=en)
- Dataprep: jobs. *How are Dataprep jobs created and run? What permissions do you need? A term I saw was that this is a more ‘casual’ way of data cleaning. Dataproc/Dataflow would be more programmatic and therefore ‘intense’, I suppose.*[https://cloud.google.com/dataprep/docs/html/Jobs-Page_57344842](https://cloud.google.com/dataprep/docs/html/Jobs-Page_57344842)
- DataStudio: visualisation. *What are the causes of stale data? And how do you get the latest? What caching options do you need to set?*
- Machine Learning : feature crosses. *Learn what these are and what issues it solves.*[https://developers.google.com/machine-learning/crash-course/feature-crosses/video-lecture](https://developers.google.com/machine-learning/crash-course/feature-crosses/video-lecture)
- Machine Learning. *Go through the Coursera course on machine learning.*[https://www.coursera.org/learn/serverless-machine-learning-gcp/home/welcome](https://www.coursera.org/learn/serverless-machine-learning-gcp/home/welcome)
- Machine Learning: Dealing with overfitting.[https://developers.google.com/machine-learning/crash-course/generalization/peril-of-overfitting](https://developers.google.com/machine-learning/crash-course/generalization/peril-of-overfitting)
- Machine Learning: Regularization. *What does it mean to increase or decrease regularization?*[https://www.coursera.org/lecture/deep-neural-network/why-regularization-reduces-overfitting-T6OJj](https://www.coursera.org/lecture/deep-neural-network/why-regularization-reduces-overfitting-T6OJj)
- Dataproc: how to control scaling? Configure autoscaling?[https://cloud.google.com/dataproc/docs/concepts/configuring-clusters/autoscaling](https://cloud.google.com/dataproc/docs/concepts/configuring-clusters/autoscaling)
- Avro file format. This is a compressed format that bigquery/dataflow can work with it directly.[https://cloud.google.com/bigquery/docs/loading-data-cloud-storage-avro](https://cloud.google.com/bigquery/docs/loading-data-cloud-storage-avro?authuser=0)
- Know a bit about other technologies outside of just GCP also. Remember that as a Professional on GCP, you are also expected to know technologies in the general ecosystem. You might have to decide between GCP solutions and alternatives in the market. Just by-hearting GCP won’t cut it.
- Key Management Service. Using KMS with non-GCP products. *Note that there is a default key management where Google manages all the keys, then there is a customer managed encryption keys, and also a customer supplied encryption keys.*[https://cloud.google.com/kms/docs/](https://cloud.google.com/kms/docs/)
- BigQuery query plan. *BigQuery allows you to see the query plan and execution profile for queries that you run. Know the phases, difference between average and max time, why there can be skew in the plan, and how to optimize for it.*[https://cloud.google.com/bigquery/query-plan-explanation](https://cloud.google.com/bigquery/query-plan-explanation)
- BigQuery + GCS. Know how to link tables between GCS and BigQuery as permanent tables and temporary tables.[https://cloud.google.com/bigquery/external-data-cloud-storage](https://cloud.google.com/bigquery/external-data-cloud-storage)
- You don’t have to by-heart the case studies, but study them well. Work through solutioning for it by yourself. The Linux Academy course has a module that goes over the case studies. (I believe the updated exam has no more case studies.)
- Bigquery. Know what a federated table is. While you are at it, learn also about clustered tables.[https://cloud.google.com/bigquery/external-data-sources](https://cloud.google.com/bigquery/external-data-sources)

1. Storage is one of most important aspect in GCP Data Engineering exam. At 15–20 questions will be coming from this section. Apparently, this section looks easy in compare with AI or Dataflow, DO NOT TAKE THIS TOPIC LIGHTLY. This is main section where you have to score 100%. Read everything from Google Documentation regarding BigQuery (everything !!). Learn the use cases where you can use BigQuery and BigTable. Learn completely about Cloud Storage. Learn all the case studies published in Google Cloud related to Cloud Storage. You can expect 15 questions from this.

1. A very good understanding about the Hadoop ecosystem. What are different components evolving Hadoop Eco System (Map-Reduce paradidgm, Columnar Data Storage, NoSQL DB, Hive, HBase, jobs). You can expect around 10 questions from this section.

1. Streaming Data processing is one of the difficult section (according to mine) in GCP. You should have the complete grip on Windowing functionality and what are the basic usage of different Window Types. Cloud PubSub and Apache Kafka with Cloud Storage/Big Query/Big Table. You can expect 4–8 questions from this section.

1. Different use Cases of Migrating on-premise Hadoop Cluster to Google Cloud Platform. There could be multiple answers for this type of questions. You have to be careful answering these questions. The key could be hidden in the statement. The statement for these questions are very big. If you’re not sure, mark these for later review. There are different [Youtube Videos](https://www.youtube.com/watch?v=h1LvACJWjKc) which you can refer. There are 3–7 questions from this section. It is important to know the [concepts of Dataproc](https://cloud.google.com/dataproc/docs/concepts)

1. I could not find any specific question only dealing with App Engine or Compute Engine, but the questions could be coming in combination with Cloud Dataproc with one Master Node with some specification and Worker Node with some other specification. Now, question could be asked to build a Lift and Shift Hadoop Cluster what are different configuration you’ll prefer.

1. Some questions are dealing with SSD Vs HDD, Persistent Storage (Ephemeral vs non-ephemeral), Nearline Vs Coldline, HDFS Vs Cloud Storage. There will definitely 2 questions on that.

1. Understanding Vision API, Natural Language Processing API. Understand how call these API using Service Call and what are the different output with different parameters. You can expect around 5 questions from this.

1. IAM and Admin — Frankly speaking, I am not confident about this. I just read in theory and never tried to experiment with real GCP environment. I found this section little difficult to understand. In my paper, I got 5–7 questions on this related to access, API Key, Service Account. Try to learn how many different options you’ve in order to provide access, There should not be any direct question, but, questions can be asked in combination with Stackdriver Motioning log file or Google Storage access in the account/project level/account level.

1. Stackdriver Monitoring ([Read this Blog](https://cloud.google.com/blog/products/gcp/google-stackdriver-generally-available)) and Google Datalab are two areas which is related to almost 10% of the questions from the above sections. There cold not be any direct questions from these, but in order to answer the questions asked, a very good understanding of these topics are essential.

# Blog 8

## **1. I started with [Coursera: Data Engineering, Big Data, and Machine Learning on GCP Specialization](http://data%20engineering%2C%20big%20data%2C%20and%20machine%20learning%20on%20gcp%20specialization/):**

**Time needed**: about 4+ weeks on a 20 hours study week**Readiness for exam upon completion**: 40%**Price**: $49 USD/month with 7 days trial

This course is a good introduction to the Google Cloud Platform, what products are out there and what they do. There is a combination of presentations, demos, and hands-on labs, participants will learn how to design data processing systems, build end-to-end data pipelines, analyze data and carry out machine learning. The course covers structured, unstructured, and streaming data. Coursera alone is definitely not enough to pass the exam — do not just rely on the training materials and Coursera, but use your own experience in developing via the hands-on Qwiklabs.

And mind you, there is a *lot* of info in this course, especially for someone new to GCP. I actually stopped mid-way just to take a breath from the sea of information, and found another course that gives you a comprehensive overview on all the products in a much shorter time span. See below.

## **2. I then found and took [Sam Lee](https://medium.com/u/46b7e98cb00f?source=post_page-----663b2dfac492--------------------------------)’s [Google Cloud Professional Data Engineer Express Course](https://www.udemy.com/course/learn-gcp-become-a-certified-data-engineer-express-course/):**

**Time needed**: 4.5 hours**Readiness for exam upon completion**: 20%**Price**: CAD $24.99/lifetime access with community support

This course is legit right under 5 hours, and walks you through all the major products you need to know for the exam. It’s a short and sweet resource to give you a big picture of what you need to know for each product on the exam. I’m a big-picture kind of person, so going through this course really helped me gain a perspective of what exactly I’m going into, before I dig down to the details.

## **3. I then finished the [Data Engineer Course on Linux Academy](https://linuxacademy.com/google-cloud-platform/training/course/name/google-cloud-data-engineer) by [Matthew Ulasien](https://medium.com/u/e3f177c8df80?source=post_page-----663b2dfac492--------------------------------)**

**Time needed**: 20+ hours**Readiness for exam upon completion**: 80%**Price**: $49 USD/month with 7 days trial

I must say that this is a phenomenal resource. There is a combination of 73 videos, 6 hands-on labs, and 7 practice quizzes/exams in this course, and note that some of the practice questions in this course actually appears on the exam. This course comes with the [Data Dossier eBook](https://www.lucidchart.com/documents/view/0ca44a63-4ea4-4d78-8367-2465512d21be/1) (essentially the collated course materials) which is basically like a in-depth cheat-sheet for all the systems.

I would say these three resources are enough to provide you with most of the content you need to know for the exam.

**And now to the ultimate hack that helped me ace the exam.**
 If you do exactly the actions I outlined in the “how to solve” section below, you shouldn’t have a problem passing the exam.

1. **Product Functionality Questions (about 20–30%)Example exam questions:** *your company is streaming loT sensors, which products would you use to design a data pipeline? You need cloud storage systems that support JSON and ANSI SQL, which product should you use?***How to solve:** Going through all the courses on either Coursera or Linux will be more than enough to help you get to this level.
2. **Product Operational Questions (about 30–40%)Example exam questions:** *if visualization data is not showing in Data Studio, what should you do? Which proxy do you use to access the YARN web interface? This query returns an error, what should you do to fix it?***How to solve**: the core of this type of question is “best practice”. There are two parts to solving this. One is playing with the platform, interacting with it, and know the settings and toggle options. Don’t worry, you don’t have to spend days doing Qwiklabs. Just watch all the hands-on videos on Linux Academy in detail, identify the systems that you are less familiar with or find more complicated, and do the Qwiklabs for these. If you’re time-bound, you really don’t need to go through every lab. I didn’t touch the Coursera labs at all. Additionally, do practice exams while going over the [GCP documentation](https://cloud.google.com/docs/) to understand what GCP’s *recommended best practices* are. Here are some examples of documentation:[BigQuery best practices](https://cloud.google.com/bigquery/docs/best-practices)[Stackdriver](https://thenewstack.io/closer-look-google-stackdriver/) summary[BigTable](https://cloud.google.com/bigtable/docs/performance) and understand how to design a good schema[IAM](https://cloud.google.com/iam/docs/concepts) to get familiar with the basic concepts and rolesA great list of [resource dump](https://docs.google.com/spreadsheets/d/1LUtqhOEjUMySCfn3zj8Arhzcmazr3vrPzy7VzJwIshE/edit?usp=sharing&source=post_page-----bb6a0812a1b1----------------------) by
    
    [Ivam Luz](https://medium.com/u/8f3c967e1c89?source=post_page-----663b2dfac492--------------------------------)
    
3. **General Machine Learning Questions (about 20–30%)Example exam questions:** *what parameters are adjusted by a neural network during training? Your company wants to predict stock prices, what ML model would you train? Shown a graph of data points, what equation do you need to cluster them (e.g. cos(X) or X²+Y²)?***How to solve:** training material ain’t gonna cut it. Some of these questions are not on Linux or Coursera. You need to do your own research. Don’t fret about this too much — you’ll likely be able to answer most of these questions by learning about how TensorFlow, GCP’s AI Products, and pre-trained models work. Here are some focus areas that appeared on my October 2019 exam which might be helpful:[How to fix over/underfitting](https://www.tensorflow.org/tutorials/keras/overfit_and_underfit)[Know what dropout methods are](https://en.wikipedia.org/wiki/Dropout_(neural_networks))[Understand L1/L2 regularization](https://towardsdatascience.com/l1-and-l2-regularization-methods-ce25e7fc831c?gi=b89612114f53)[Understand synthetic features](https://developers.google.com/machine-learning/crash-course/feature-crosses/video-lecture)[Google Machine Learning (ML) APIs](https://cloud.google.com/products/ai/)[Google Cloud Machine Learning Engine](https://cloud.google.com/ml-engine/)[Google Cloud TPUs](https://cloud.google.com/tpu/)[Google Glossary of ML terms](https://developers.google.com/machine-learning/glossary/)

# Blog 9

Usually, these are the steps I follow when I decide to take a certification:

1. Read the exam overview: [Professional Cloud Architect](https://cloud.google.com/certification/cloud-architect) and [Professional Data Engineer](https://cloud.google.com/certification/data-engineer);
2. Read the exam guide: [Professional Cloud Architect](https://cloud.google.com/certification/guides/professional-cloud-architect/) and [Professional Data Engineer](https://cloud.google.com/certification/guides/data-engineer/);
3. Next, I visit the products page of the platform and identify each product that may be related to the topics listed on the exam guide. For GCP, you can find this list [here](https://cloud.google.com/products/).
4. For each of the products identified in the prior step, I visit its **Documentation / Concepts** **page** and start reading about each of the concepts that I consider relevant for the given product. Check the [GCE concepts page](https://cloud.google.com/compute/docs/concepts), for example.
5. You’ll probably notice some products seem to overlap with each other and find it difficult to known when to use one or the other. Google Search is your best friend here :)
6. After I go through each product and its concepts, I read the sample study cases provided by Google and try to design potential solutions that could address the requirements described on them. For the **Professional Data Engineer** exam, the sample study cases have been **recently removed**. For the **Professional Cloud Architect** exam, you can find the sample study cases at the end of the [exam guide](https://cloud.google.com/certification/guides/professional-cloud-architect/).
7. Finally, I take the practice exam (**[Professional Cloud Architect](https://cloud.google.com/certification/practice-exam/cloud-architect)** and **[Professional Data Engineer](https://cloud.google.com/certification/practice-exam/data-engineer?hl=vi))**. The practice exam provides an explanation for each of the questions after you finish and is very good to have an idea of the format of the questions you’ll face and how prepared you are.
8. After I finish the practice exam, I take notes of the topics I didn’t go well and re-read the relevant documentation I collected on **step 4** above.
9. I will then take the practice exam again (you can take it as many times as you want) and keep repeating steps from 6 to 8 until I feel confident to take the exam.

****Tips for taking your exam****
1. Know what each product does, what it’s good for and what it’s not good for, as well as its billing characteristics;
2. As described before, you have 2 hours to finish the exam. Keep in mind that **good time management is crucial for your success**;
3. **Don’t spend too much time on questions you don’t know**. If you aren’t sure about an answer, mark the question to be reviewed later and move on to the next questions.
4. **Practice as much as possible using the practice exams**.

# Blog 10

1. First complete Coursera Data Engineer specialization — [https://www.coursera.org/specializations/gcp-data-machine-learning?](https://www.coursera.org/specializations/gcp-data-machine-learning?)(**very important don’t skip)**

2. Udemy course — [https://www.udemy.com/gcp-data-engineer-and-cloud-architect/](https://www.udemy.com/gcp-data-engineer-and-cloud-architect/) (concepts are made easy to understand)

3. ML crash course — [https://developers.google.com/machine-learning/crash-course/ml-intro](https://developers.google.com/machine-learning/crash-course/ml-intro) (**very important don’t skip)**

4. Developer cheat sheet — [https://docs.google.com/spreadsheets/d/1OkFbizpnc_iyzcApqRrqsNtUVazKJDtCyH5vw3352xM/edit#gid=1557314907](https://docs.google.com/spreadsheets/d/1OkFbizpnc_iyzcApqRrqsNtUVazKJDtCyH5vw3352xM/edit#gid=1557314907)

5. Explore and document all the sources and destinations supported for each GCP service — **very important**

6. Big Query

- [https://cloud.google.com/bigquery/docs/](https://cloud.google.com/bigquery/docs/) — go through entire Big query documentation, don’t skip any topic. Very important to understand all the concepts of Big query
- Legacy & Standard Sql difference
- Big query best practices in terms of cost & performance
- Big Query transfer service –understand what all sources supported for Big query transfer service
- Partitions — [https://cloud.google.com/bigquery/docs/partitioned-tables](https://cloud.google.com/bigquery/docs/partitioned-tables)
- Clustering
- Authorized views
- Big Query ML — [https://cloud.google.com/bigquery/docs/bigqueryml-intro](https://cloud.google.com/bigquery/docs/bigqueryml-intro)
- Streaming Inserts — [https://cloud.google.com/bigquery/streaming-data-into-bigquery](https://cloud.google.com/bigquery/streaming-data-into-bigquery) & [https://cloud.google.com/bigquery/quotas#streaming_inserts](https://cloud.google.com/bigquery/quotas#streaming_inserts)
- Federated sources
- Understand the concept of permanent & temporary tables in Big query
- Big query cache
- Schema auto detect
- load multiple files into Big query
- Big Query IAM roles & permissions
- Methods to increase the number of [concurrent slots](https://cloud.google.com/bigquery/quotas#query_jobs) — [https://cloud.google.com/bigquery/quotas#query_jobs](https://cloud.google.com/bigquery/quotas#query_jobs)
- Big query metrics in stack driver
- Audit logs
- Performing ETL from a Relational Database into BigQuery — [https://cloud.google.com/solutions/performing-etl-from-relational-database-into-bigquery](https://cloud.google.com/solutions/performing-etl-from-relational-database-into-bigquery)
- Point in time snapshots BigQuery
- UDFs — [https://cloud.google.com/bigquery/docs/reference/standard-sql/user-defined-functions](https://cloud.google.com/bigquery/docs/reference/standard-sql/user-defined-functions)
- Understand the pros and cons of denormalized data in the context of BigQuery — [https://cloud.google.com/bigquery/docs/loading-data#loading_denormalized_nested_and_repeated_data](https://cloud.google.com/bigquery/docs/loading-data#loading_denormalized_nested_and_repeated_data)

7. Pubsub

- [https://cloud.google.com/pubsub/docs/](https://cloud.google.com/pubsub/docs/) — Very important to understand all the concepts of Pubsub
- Understand the concept of Publisher, subscriber & Topic
- Push & Pull subscriptions & which provides good & consistent performance in terms of real time
- Migrate from Kafka to PubSub — [https://cloud.google.com/blog/products/gcp/apache-kafka-for-gcp-users-connectors-for-pubsub-dataflow-and-bigquery](https://cloud.google.com/blog/products/gcp/apache-kafka-for-gcp-users-connectors-for-pubsub-dataflow-and-bigquery)
- Pusub metrics in stackdriver — [https://cloud.google.com/pubsub/docs/monitoring](https://cloud.google.com/pubsub/docs/monitoring)
- Ordering of messages — [https://cloud.google.com/pubsub/docs/ordering](https://cloud.google.com/pubsub/docs/ordering)
- Dealing with duplicate messages — [https://cloud.google.com/pubsub/docs/pull#dupes](https://cloud.google.com/pubsub/docs/pull#dupes)
- Pubsub IAM roles & permissions

8. Dataflow

- [https://cloud.google.com/dataflow/docs/](https://cloud.google.com/dataflow/docs/) — Very important to understand all the concepts of Dataflow
- Apache beam building blocks (Pipeline, PCollection, PTransform, ParDO ) — [https://beam.apache.org/documentation/programming-guide/](https://beam.apache.org/documentation/programming-guide/)
- Windowing concepts (Fixed, Session, Sliding, Global windows) — [https://beam.apache.org/documentation/programming-guide/#provided-windowing-functions](https://beam.apache.org/documentation/programming-guide/#provided-windowing-functions)
- Side Inputs — [https://beam.apache.org/documentation/programming-guide/#side-inputs](https://beam.apache.org/documentation/programming-guide/#side-inputs)
- Side Outputs — [https://cloud.google.com/blog/products/gcp/handling-invalid-inputs-in-dataflow](https://cloud.google.com/blog/products/gcp/handling-invalid-inputs-in-dataflow)
- Exactly once processing of Pub Sub messages — [https://cloud.google.com/blog/products/gcp/after-lambda-exactly-once-processing-in-cloud-dataflow-part-3-sources-and-sinks](https://cloud.google.com/blog/products/gcp/after-lambda-exactly-once-processing-in-cloud-dataflow-part-3-sources-and-sinks)
- Data flow IAM roles & permissions
- Dataflow metrics in stack driver
- How to automate dataflow job using cloud composer

9. BigTable

- [https://cloud.google.com/bigtable/docs/](https://cloud.google.com/bigtable/docs/) — Very important to understand all the concepts of BigTable
- Understand architecture and key reasons for high performance well — [https://cloud.google.com/bigtable/docs/overview](https://cloud.google.com/bigtable/docs/overview) & [https://cloud.google.com/bigtable/docs/performance](https://cloud.google.com/bigtable/docs/performance)
- Key visualizer — [https://cloud.google.com/bigtable/docs/keyvis-overview](https://cloud.google.com/bigtable/docs/keyvis-overview)
- Scaling up cloud bigtable — [https://cloud.google.com/bigtable/docs/scaling](https://cloud.google.com/bigtable/docs/scaling) & [https://cloud.google.com/bigtable/docs/modifying-instance](https://cloud.google.com/bigtable/docs/modifying-instance)
- Performant key/schema design — [https://cloud.google.com/bigtable/docs/schema-design](https://cloud.google.com/bigtable/docs/schema-design) & [https://cloud.google.com/bigtable/docs/schema-design-time-series](https://cloud.google.com/bigtable/docs/schema-design-time-series)
- Dev to Prod cluster promotion
- HDD to SSD data migration — [https://cloud.google.com/bigtable/docs/choosing-ssd-hdd](https://cloud.google.com/bigtable/docs/choosing-ssd-hdd)
- Replication & App profiles — [https://cloud.google.com/bigtable/docs/replication-overview](https://cloud.google.com/bigtable/docs/replication-overview) & [https://cloud.google.com/bigtable/docs/app-profiles](https://cloud.google.com/bigtable/docs/app-profiles)
- Big Table IAM roles & permissions
- Hbase shell & CBT tool
- Dataflow & Dataproc connectors for Big Table
- BigTable IAM roles & permissions
- BigTable metrics in stack driver
- Audit logging

10. Dataproc

- [https://cloud.google.com/dataproc/docs/](https://cloud.google.com/dataproc/docs/) — understand all the concepts of Dataproc
- Cloud storage connector — [https://cloud.google.com/dataproc/docs/concepts/connectors/cloud-storage](https://cloud.google.com/dataproc/docs/concepts/connectors/cloud-storage)
- Big Query connector — [https://cloud.google.com/dataproc/docs/concepts/connectors/bigquery](https://cloud.google.com/dataproc/docs/concepts/connectors/bigquery)
- Big Table connector — [https://cloud.google.com/dataproc/docs/concepts/connectors/cloud-bigtable](https://cloud.google.com/dataproc/docs/concepts/connectors/cloud-bigtable)
- Dataproc IAM roles & permissions
- Pre-emptible workers — [https://cloud.google.com/dataproc/docs/concepts/compute/preemptible-vms](https://cloud.google.com/dataproc/docs/concepts/compute/preemptible-vms)
- Scaling clusters — [https://cloud.google.com/dataproc/docs/concepts/configuring-clusters/scaling-clusters](https://cloud.google.com/dataproc/docs/concepts/configuring-clusters/scaling-clusters)

11. Cloud Storage

- Data transfer services — Transfer service, Transfer appliance, using gsutil parallel uploads & multithreading
- How to transfer small files on prem to cloud storage bucket
- How to transfer large files on prem to cloud storage bucket
- continuously sync data between on-prem and GCP — -[https://cloud.google.com/storage/docs/gsutil/commands/rsync](https://cloud.google.com/storage/docs/gsutil/commands/rsync)
- How Dedicated Interconnect impacts your data transfer decisions?

12. Cloud Sql

- [https://cloud.google.com/sql/docs/](https://cloud.google.com/sql/docs/) — Cloud sql concepts
- Read replicas
- Export data from cloudsql & import into bigquery

13. Cloud Spanner

- [https://cloud.google.com/spanner/docs/](https://cloud.google.com/spanner/docs/) — Cloud spanner concepts
- Primary & Secondary indexes

14. Cloud composer

- [https://cloud.google.com/composer/](https://cloud.google.com/composer/) — Understand the concepts of cloud composer

15. Firestore & Datastore

- [https://cloud.google.com/firestore/docs/](https://cloud.google.com/firestore/docs/) — firestore concepts
- [https://cloud.google.com/datastore/docs/](https://cloud.google.com/datastore/docs/) — Datastore concepts
- how to [backup, migrate Datastore](https://cloud.google.com/datastore/docs/schedule-export)
- Datastore — Kind, Entities, Properties, namespaces, multitenant, single & composite indexes
- Firestore — Collections, Documents, fields, indexes
- Features and difference between Firestore with Datastore & Firestore Native modes

16. Memorystore

- Understand just the concept — [https://cloud.google.com/memorystore/docs/redis/](https://cloud.google.com/memorystore/docs/redis/) — mentioned in syllabus, but I did not get any question on this

17. Dataprep

- [https://cloud.google.com/dataprep/docs/](https://cloud.google.com/dataprep/docs/) — Dataprep concepts
- Recipes & transforms
- How to automate Dataprep jobs using cloud composer

18. Datastudio

- Datastudio concepts — [https://support.google.com/datastudio/answer/6283323?hl=en&ref_topic=6267740](https://support.google.com/datastudio/answer/6283323?hl=en&ref_topic=6267740)
- How to enable cache — [https://support.google.com/datastudio/answer/7020039?ref_topic=6309857](https://support.google.com/datastudio/answer/7020039?ref_topic=6309857)

19. Machine learning

- Supervised learning, Unsupervised learning, Reinforcement learning,
- Know best practices for training ML models (training, test, overfitting/under fitting detection)
- Specifying machine types or scales — [https://cloud.google.com/ml-engine/docs/tensorflow/machine-types](https://cloud.google.com/ml-engine/docs/tensorflow/machine-types)
- Understand when to use TPUs & GPUs
- Understand Weights, Biases, Gradient decent, Hyper parameter tuning, Regularization, Feature engineering, Feature crossing, Embedding
- Know basic ML algorithms –Linear regression, Logistic regression, Clustering, Association
- Wide and Deep neural networks
- how to deploy models on CloudML engine
- AI & Machine learning products (Vison API, Natural language, Video Intelligence, Speech to text) — -[https://cloud.google.com/products/ai/](https://cloud.google.com/products/ai/) — understand the difference between AUTO ML custom models and ML Pre-trained model APIs
- Understand Dataloss prevention — [https://cloud.google.com/dlp/docs/](https://cloud.google.com/dlp/docs/)
- Understand Dialogflow — [https://cloud.google.com/dialogflow-enterprise/docs/](https://cloud.google.com/dialogflow-enterprise/docs/)
- Kubeflow is mentioned in the syllabus, but I did not get any question on this. Better to understand what it is.

20. Stack driver

- Monitoring, Alerting, Logging
- Basic and Advanced filter logs
- What all sources and sinks supported
- Audit logs
- Managing Exports

21. IAM

- Roles & Permissions
- Hierarchy
- Service Account
- How to allow cross team data access to BigQuery and GCS in a large organization

22. Encryption

- [https://cloud.google.com/blog/products/gcp/managing-encryption-keys-in-the-cloud-introducing-google-cloud-key-management-service?m=1](https://cloud.google.com/blog/products/gcp/managing-encryption-keys-in-the-cloud-introducing-google-cloud-key-management-service?m=1)
- Data encryption options — [https://cloud.google.com/storage/docs/encryption/](https://cloud.google.com/storage/docs/encryption/)
- Client side encryption
- Server side encryption
- Default encryption
- Customer supplied encryption keys
- Customer managed encryption keys

23. Networking at a high level

- Understand the types of network at a high level — vpc, vpn, dedicated interconnect & partner interconnect. Don’t get into depth of understanding these concepts for Data engineer exam

24. BigQuery, BigTable, Cloud SQL, Cloud Storage to be able to find the cheapest product for a set of availability/durability criteria.

25. **Gain Solution Design Experience**

Review the cloud infrastructure solutions at [Google Cloud Solutions](https://cloud.google.com/solutions/) under the following categories of data processing, data warehousing, analytics and visualization, IoT , etc.

1. Data Processing
- [Data Lifecycle on Google Cloud Platform](https://cloud.google.com/solutions/data-lifecycle-cloud-platform)
- [Build a Data Lake on Google Cloud Platform](https://cloud.google.com/solutions/build-a-data-lake-on-gcp)
- [Migrating Hadoop Jobs from On-Premises to Google Cloud Platform](https://cloud.google.com/solutions/migration/hadoop/hadoop-gcp-migration-jobs)
- [Migrating HDFS Data from On-Premises to Google Cloud Platform](https://cloud.google.com/solutions/migration/hadoop/hadoop-gcp-migration-data)
- [Architecture: Apache Spark & Hadoop on Google Cloud Platform](https://cloud.google.com/solutions/migration/hadoop/hadoop-gcp-migration-overview)
- [Running RStudio® Server on a Cloud Dataproc Cluster](https://cloud.google.com/solutions/running-rstudio-server-on-a-cloud-dataproc-cluster)
- [Architecture: Complex Event Processing](https://cloud.google.com/solutions/architecture/complex-event-processing)

2. Data Warehouse

- [BigQuery for Data Warehouse Practitioners](https://cloud.google.com/solutions/bigquery-data-warehouse)
- [Performing ETL from a Relational Database into BigQuery](https://cloud.google.com/solutions/performing-etl-from-relational-database-into-bigquery)
- [Build a Marketing Data Warehouse on Google Cloud Platform](https://cloud.google.com/solutions/marketing-data-warehouse-on-gcp)

3. Business Intelligence (Analytics and Visualization)

- [Creating an Authorized View in BigQuery](https://cloud.google.com/bigquery/docs/share-access-views)
- [Architecture: Optimizing Large-Scale Ingestion of Analytics Events and Logs](https://cloud.google.com/solutions/architecture/optimized-large-scale-analytics-ingestion)
- [Building a Mobile Gaming Analytics Platform — a Reference Architecture](https://cloud.google.com/solutions/mobile/mobile-gaming-analysis-telemetry)
- [Creating Custom Interactive Dashboards with Bokeh and BigQuery](https://cloud.google.com/solutions/bokeh-and-bigquery-dashboards)
- [Visualizing BigQuery Data Using Google Cloud Datalab](https://cloud.google.com/bigquery/docs/visualize-jupyter)
- [Visualizing BigQuery Data Using Google Data Studio](https://cloud.google.com/bigquery/docs/visualize-data-studio)

4. Machine Learning

- [Building a Serverless Machine Learning Model](https://cloud.google.com/solutions/building-a-serverless-ml-model)
- [Architecture of a Serverless Machine Learning Model](https://cloud.google.com/solutions/architecture-of-a-serverless-ml-model)
- [Using Cloud Dataﬂow for Batch Predictions with TensorFlow](https://cloud.google.com/solutions/using-cloud-dataflow-for-batch-predictions-with-tensorflow)
- [Running R at Scale on Compute Engine](https://cloud.google.com/solutions/running-r-at-scale)
- [Using Distributed TensorFlow with Cloud ML Engine and Cloud Datalab](https://cloud.google.com/ml-engine/docs/tensorflow/distributed-tensorflow-mnist-cloud-datalab)
- [Creating an Object Detection Application Using TensorFlow](https://cloud.google.com/solutions/creating-object-detection-application-tensorflow)
- [Using Machine Learning on Compute Engine to Make Product Recommendations](https://cloud.google.com/solutions/recommendations-using-machine-learning-on-compute-engine)
- [Optical Character Recognition (OCR) Tutorial](https://cloud.google.com/functions/docs/tutorials/ocr)
- [An Image Search Application that Uses the Cloud Vision API](https://cloud.google.com/solutions/image-search-app-with-cloud-vision)
- [Considerations for Sensitive Data within Machine Learning Datasets](https://cloud.google.com/solutions/sensitive-data-and-ml-datasets)

5. IoT

- [Overview of Internet of Things](https://cloud.google.com/solutions/iot-overview)
- [Architecture: Real-Time Stream Processing for IoT](https://cloud.google.com/solutions/big-data/stream-analytics/)
- [Automating IoT Machine Learning: Bridging Cloud and Device Beneﬁts with Cloud ML Engine](https://cloud.google.com/solutions/automating-iot-machine-learning)
- [Oil and Gas Equipment Monitoring and Analytics](https://cloud.google.com/solutions/oil-and-gas-equipment-monitoring-and-analytics)
- [Designing a Connected Vehicle Platform on Cloud IoT Core](https://cloud.google.com/solutions/designing-connected-vehicle-platform)

26. Acquire Hands-On Experience

Complete a set of self-paced labs around Cloud Infrastructure to gain hands-on experience.

**27. Qwiklabs Quests**

Completion of the following quests are highly recommended:

1. [GCP Essentials](https://google.qwiklabs.com/quests/23)
2. Advanced: [Data Science on the Google Cloud Platform](https://google.qwiklabs.com/quests/43?locale=en) (9 labs)
3. Advanced: [Machine Learning APIs](https://google.qwiklabs.com/quests/32?locale=en) (8 labs)
4. Advanced: [Scientiﬁc Data Processing](https://google.qwiklabs.com/quests/28?locale=en) (7 labs)
5. Expert: [Google Cloud Solutions II: Data and Machine Learning](https://google.qwiklabs.com/quests/38?locale=en) (10 labs)

27. Attempt the Practice exams only after you are good with above concepts. Actual exam is bit tough than the practice questions I mentioned below.

- [https://www.udemy.com/google-cloud-certified-professional-data-engineer-practice-exams/](https://www.udemy.com/google-cloud-certified-professional-data-engineer-practice-exams/)
- [Data & Big Data](https://docs.google.com/forms/d/e/1FAIpQLSe9qR0aXWX54BkTZi134hVGkBE-hNwDI5b8SCEbqNInyLs2rQ/viewform)

28. Few other links:

- [GoogleCloudPlatform/training-data-analyst: Labs and demos for courses for GCP Training (http://cloud.google.com/training).](https://github.com/GoogleCloudPlatform/training-data-analyst)
- [Google Codelabs](https://codelabs.developers.google.com/)
- [Google Cloud Platform — Community — Medium](https://medium.com/google-cloud)
- [Google Cloud Platform Blog](https://cloudplatform.googleblog.com/)
- [Google Cloud Big Data and Machine Learning Blog | Google Cloud](https://cloud.google.com/blog/big-data/)
- [Data Analytics | Google Cloud Blog](https://cloud.google.com/blog/products/data-analytics)
- [Google Cloud Blog | News, Features and Announcements](https://cloud.google.com/blog/)
- [https://www.facebook.com/googlecloud/](https://www.facebook.com/googlecloud/)
- [Cloud Solutions | Google Cloud](https://cloud.google.com/solutions/)
- Read the [Site Reliability Engineering](https://landing.google.com/sre/sre-book/toc/) Book , especially the Chapter 25 (Data Processing Pipelines), Chapter 26 (Data Integrity: What You Read Is What You Wrote).

# Blog 11

Here is what all is covered:

## **Cloud Storage and Cloud Datastore**

Surprisingly, these products are not covered much in the exam, perhaps because they are covered more extensively in the Cloud Architect exam. Just know the basic concepts of each product and when it is appropriate (or not appropriate) to use each product, and you should be well covered.

## **Cloud SQL**

There were surprisingly few questions on this product in the exam. If you have practical experience using the product, you should be fine to answer any questions that may come up. As with questions related to other data storage products, be sure to know in what scenarios it is appropriate to use Cloud SQL and when it would be more appropriate to use Datastore, Bigquery, Bigtable, etc.

## **Bigtable**

This product is covered quite extensively in the exam. You should at least know the basic concepts of the product, such as

- how to [design an appropriate schema and row key](https://cloud.google.com/bigtable/docs/schema-design)
- [Instances, Cluster and Nodes](https://cloud.google.com/bigtable/docs/instances-clusters-nodes)
- whether Bigtable supports transactions and ACID operations
- [CBT tool](https://cloud.google.com/bigtable/docs/cbt-overview)
- [Schema design for time series data](https://cloud.google.com/bigtable/docs/schema-design-time-series)
- [Access control in Bigtable](https://cloud.google.com/bigtable/docs/access-control)
- what the [size limits for Bigtable](https://cloud.google.com/bigtable/quotas) are (cell and row size, maximum number of tables, etc).

## **BigQuery**

BigQuery will be covered in greater details in exam. If you know BigQuery, you will be able to answer approximately 40% questions in exam. You should know about:

- the basic capabilities of BigQuery and what kind of problem domains it is suitable for.
- BigQuery security and the level at which security can be applied (project and datastore level, but not table or view level)
- [Partitioned tables](https://cloud.google.com/bigquery/docs/partitioned-tables), [wildcard queries](https://cloud.google.com/bigquery/docs/querying-wildcard-tables) (“backtick” syntax)
- [Views](https://cloud.google.com/bigquery/docs/views-intro) and their usage scenarios
- [Importing/Exporting](https://cloud.google.com/bigquery/docs/storing-data) data to/from BigQuery
- have an understanding of the methods available to connect external systems or tools to BigQuery for analytics purposes
- how the BigQuery billing model works, and who gets billed when queries cross project and billing account boundaries
- [Access control in BigQuery](https://cloud.google.com/bigquery/docs/access-control)
- BigQuery [best practices](https://cloud.google.com/bigquery/docs/best-practices-costs)
- [Query plan explanation](https://cloud.google.com/bigquery/query-plan-explanation)
- [Legacy v/s Standard SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/migrating-from-legacy-sql)

## **Pub/Sub**

The exam contains lots of questions on this product, but all reasonably high level so it’s just important to know the basic concepts (topics, subscriptions, push and pull delivery flows, etc). Most importantly you should know when it is appropriate to introduce Pub/Sub as a messaging layer in an architecture, for a given set of requirements.

## **Apache Hadoop**

Technically not part of Google Cloud Platform, but there are a few questions around this technology in the exam, since it is the underlying technology for Dataproc. Expect some questions on what HDFS, Hive, Pig, Oozie or Sqoop are, but basic knowledge on what each technology is and when to use it should be sufficient.

## **Cloud Dataflow**

Lots of questions on this product, which is not surprising as it is a key area of focus for Google with regard to data processing on Google Cloud Platform. In addition to knowing the basic capabilities of the product, you will also need to understand concepts like:

- [Windowing](https://beam.apache.org/documentation/programming-guide/#windowing)
- [Watermarks and late data](https://beam.apache.org/documentation/programming-guide/#watermarks-and-late-data)
- [Triggers](https://beam.apache.org/documentation/programming-guide/#triggers)
- [Applying transforms](https://beam.apache.org/documentation/programming-guide/#applying-transforms)
- [PCollections](https://beam.apache.org/documentation/programming-guide/#pcollections), etc.

## **Cloud Dataproc**

Not many questions on this besides the Hadoop questions mentioned above. Just be sure to understand the differences between Dataproc and Dataflow and when to use one or the other. Dataflow is typically preferred for a new development, whereas Dataproc would be required if migrating existing on-premise Hadoop or Spark infrastructure to Google Cloud Platform without redevelopment efforts.

## **TensorFlow, Machine Learning, Cloud DataLab**

The exam contains a significant amount of questions on this. You should understand all the basic concepts of designing and developing a machine learning solution on TensorFlow, including concepts such data correlation analysis in Datalab, and overfitting and how to correct it. Detailed TensorFlow or Cloud ML programming knowledge is not required but a good understanding of machine learning design and implementation is important.

## **Stackdriver**

A surprising numbers of questions on this, given that Stackdriver is more of an “ops” product than a “data engineering” product. Be sure to know the sub-products of Stackdriver (Debugger, Error Reporting, Alerting, Trace, Logging), what they do and when they should be used.

## **Data Studio**

Not many questions on this besides [caching concepts](https://support.google.com/datastudio/answer/7020039?hl=en), setting up metrics, dimensions and filters in a report.

# **How Do I Prepare?**

Here is a number of reference courses that I went through:

- **Coursera — [Data Engineering on GCP Specialization](https://www.coursera.org/specializations/gcp-data-machine-learning) Course**

This course is divided into 5 modules with increasing complexity. The courses are driven by [Valliappa Lakshmanan](https://www.linkedin.com/in/valliappalakshmanan/) from Google. He does a pretty great job overall. Modules are shaped initially with slides and discussion, followed by Labs run through [Google Codelabs](https://codelabs.developers.google.com/) which is a free to use training platform for hands-on labs in the Google Cloud Platform. I would highly recommend these labs.

Although, this is the official Google course for the certification, but this will not be enough for the certification.

- **Linux Academy — [GCP Data Engineer](https://linuxacademy.com/linux/training/course/name/google-cloud-data-engineer) Course**

This course is driven by [Matthew Ulasien](https://www.linkedin.com/in/matthewulasien/) and he did really well in this course. This course is a must do course to understand variety of questions that you may encounter related to [official case studies](https://cloud.google.com/certification/guides/data-engineer/#sample-case-study) by Google. Also, the quizzes are good enough to test your readiness for the exam. High recommend this course.

- **Cloud Academy — [Data Engineer](https://cloudacademy.com/learning-paths/data-engineer-professional-certification-preparation-for-google-83/) course**

Last week refresher. Greatly covers ML concepts and the related questions you may encounter.

- **Official Case Studies**

Google has officially shared 2 [case studies](https://cloud.google.com/certification/guides/data-engineer/#sample-case-study). Read them thoroughly and prepare yourself for all possible questions that may appear. Approx. 20% of exam questions will come from these case studies.

- **Official Practice exam**

Once you feel confident enough to go for exam, run over this [practice exam](https://cloud.google.com/certification/practice-exam/data-engineer) shared by Google.

# Blog 12

Notes

[Google Cloud - Data Engineer Exam Study Guide](https://servian.dev/google-cloud-data-engineer-exam-study-guide-9afc80be2ee3)

# Blog 13

### BigQuery

- [Streaming data into BigQuery](https://cloud.google.com/bigquery/streaming-data-into-bigquery) - know it well.
- [High-rate streaming](https://cloud.google.com/bigquery/quotas#streaming_inserts)
- Serving large datasets to BI dashboard (focus on data freshness and cost efficiently)
- [Benefits of partitions](https://cloud.google.com/bigquery/docs/partitioned-tables)
- From the point of view of BigQuery administrator ensure that you know best practices on how to allow various teams access team specific datasets without cross access.
- Methods to increase the number of [concurrent slots](https://cloud.google.com/bigquery/quotas#query_jobs)
- [How to verify that ETL migrated to BigQuery produced equal results](https://cloud.google.com/solutions/performing-etl-from-relational-database-into-bigquery)
- Point in time snapshots BigQuery
- [Integration with BigQuery ML](https://cloud.google.com/bigquery/docs/bigqueryml-intro)
- [UDFs](https://cloud.google.com/bigquery/docs/reference/standard-sql/user-defined-functions)
- Understand the pros and cons of [denormalised data](https://cloud.google.com/bigquery/docs/loading-data#loading_denormalized_nested_and_repeated_data) in the context of BigQuery

### BigTable

- Understand [architecture](https://cloud.google.com/bigtable/docs/overview) and key reasons for [high performance](https://cloud.google.com/bigtable/docs/performance) well
- Know [Key Visualiser](https://cloud.google.com/bigtable/docs/keyvis-overview)
- Know [when to scale BigTable](https://cloud.google.com/bigtable/docs/scaling)
- Know [performant key/schema design](https://cloud.google.com/bigtable/docs/schema-design)
- [Scaling up BigTable](https://cloud.google.com/bigtable/docs/modifying-instance)
- If you need to double your reads for a prolonged period, what can you do to guarantee the same read latency?
- Dev to Prod cluster promotion
- HDD to SSD data migration

### Dataflow

- Understand [Apache Beam building blocks](https://beam.apache.org/documentation/programming-guide/) - Pipeline, PCollection, PTransform, ParDO
- Know [Side Inputs](https://beam.apache.org/documentation/programming-guide/#side-inputs)
- [Exactly once processing of PubSub messages](https://cloud.google.com/blog/products/gcp/after-lambda-exactly-once-processing-in-cloud-dataflow-part-3-sources-and-sinks)
- [Handling invalid inputs](https://cloud.google.com/blog/products/gcp/handling-invalid-inputs-in-dataflow)

### PubSub

- [Migrate from Kafka to PubSub](https://cloud.google.com/blog/products/gcp/apache-kafka-for-gcp-users-connectors-for-pubsub-dataflow-and-bigquery)
- Know potential reasons for PubSub ingesting applications being busier than initially planned
- [What PubSub metrics are available in Stackdriver and how to debug producers/consumers](https://cloud.google.com/pubsub/docs/monitoring)
- [Ordering messages](https://cloud.google.com/pubsub/docs/ordering)
- [Dealing with duplicate messages](https://cloud.google.com/pubsub/docs/pull#dupes)

### Data migrations

- Know when to use [Data Transfer Appliance](https://cloud.google.com/transfer-appliance/). Hint - slow network, huge dataset, no in-between refreshes.
- When to use [Transfer Service](https://cloud.google.com/storage-transfer/docs/) and what are its limitations.
- Know the cost of storage and availability for various products: BigQuery, BigTable, Cloud SQL, GCS to be able to find the cheapest product for a set of availability/durability criteria.
- How [Dedicated Interconnect](https://cloud.google.com/interconnect/docs/concepts/dedicated-overview) impacts your data transfer decisions?
- How to [continuously sync](https://cloud.google.com/storage/docs/gsutil/commands/rsync) data between on-prem and GCP

### Dataproc

- [Cloud Storage connector](https://cloud.google.com/dataproc/docs/concepts/connectors/cloud-storage)
- [Preemptible workers](https://cloud.google.com/dataproc/docs/concepts/compute/preemptible-vms)
- [Scaling clusters](https://cloud.google.com/dataproc/docs/concepts/configuring-clusters/scaling-clusters)

### ML

- Know best practices for training ML models (training, test, overfitting detection)
- [Speeding up TensorFlow applications](https://cloud.google.com/ml-engine/docs/tensorflow/machine-types)
- Know [Cloud Data Loss Prevention API](https://cloud.google.com/dlp/)
- Know [Cloud Natural Language API](https://cloud.google.com/natural-language/)
- Know [Cloud Vision API](https://cloud.google.com/vision/)

### IAM

- How to allow cross team data access to BigQuery and GCS in a large organisation

### Misc

- Know how to [backup, migrate Datastore](https://cloud.google.com/datastore/docs/schedule-export)
- Know [Cloud Composer](https://cloud.google.com/composer/) well

# Blog 12

Start reading [sample implementation for Spotify](https://labs.spotify.com/2016/02/25/spotifys-event-delivery-the-road-to-the-cloud-part-i/) and also the best practices for GCP products.

- [IAM](https://cloud.google.com/iam/docs/)
- [BigQuery](https://cloud.google.com/bigquery/docs/)
- [StackDriver](https://cloud.google.com/stackdriver/docs/)
- [Cloud SQL](https://cloud.google.com/sql/docs/postgres/)
- [Cloud Spanner](https://cloud.google.com/spanner/docs/)
- [BigTable](https://cloud.google.com/bigtable/docs/)
- [DataStore](https://cloud.google.com/datastore/docs/)
- [Firebase/firestore](https://firebase.google.com/docs/firestore/)
- [Storage](https://cloud.google.com/storage/docs/)
- [DataProc](https://cloud.google.com/dataproc/docs/)
- [DataFlow](https://cloud.google.com/dataflow/docs/)
- [Apache Beam](https://beam.apache.org/documentation/programming-guide/#windowing)
- [Pub/Sub](https://cloud.google.com/pubsub/docs/)
- [DataPrep](https://cloud.google.com/dataprep/docs/)

[GitHub - jorwalk/data-engineering-gcp: Data Engineering on Google Cloud Platform](https://github.com/jorwalk/data-engineering-gcp)

# Blog 13

# **Fundamental Services on Google Cloud Platform**

Your understanding of GCP should include familiarisation of the following fundamental services, categorised broadly as follows:

[https://miro.medium.com/max/1400/0*Wcxs7CSkFslrP7DO](https://miro.medium.com/max/1400/0*Wcxs7CSkFslrP7DO)

As the GCP ecosystem grows daily with new services being introduced, it is beneficial (though not necessary) to have an overview of these GCP products/services; refer to this [Google Cloud Developer’s Cheat Sheet](https://docs.google.com/spreadsheets/d/1OkFbizpnc_iyzcApqRrqsNtUVazKJDtCyH5vw3352xM/edit#gid=1557314907)

As well as individual services, you will need to understand how these services fit together in an overall data pipeline architecture depending on your perspective of data:

- Streaming or batch
- Structured or unstructured
- OLTP or OLAP usage
- Fully managed or semi-managed service
- High throughput and low latency requirements
- GB or TB or PB storage requirements
- Read/write/update requirements

The following illustrates one example for a streaming and batch pipeline architecture:

[https://miro.medium.com/max/1400/0*hHb8lOi3q3E3CBla](https://miro.medium.com/max/1400/0*hHb8lOi3q3E3CBla)

# **Machine Learning**

- Know the difference between *Regression* vs *Classification* model, *RMSE* vs *Cross Entropy*, *real-value* vs *categorical* features.
- Have an understanding of the ML terminologies — *Label, Input, Example, Training, Evaluation, Prediction, Gradient Descent, Weights, Batch Size, Epoch, Hidden Layers, Neurons, Features, Feature Engineering*. Differentiate *Accuracy* vs *Precision* vs *Recall*.
- Familiar with the process of creating a ML model from data source to creating data set for training, validation, and testing, and the need for a benchmark/heuristic.
- Know what *TensorFlow* is, and the purpose of *Cloud ML Engine*. Basic understanding of TensorFlow architecture — out of the box APIs, full control APIs, custom ML models, low level APIs and hardware types.
- Learn how to use the *Estimator API* for Linear/DNN regression/classification. Know what is a *Wide and Deep* model. Use the API for train and evaluate and how it uses checkpointing for fault tolerance and distributed processing. Understand how the *Tensorboard* is used for monitoring
- *Feature Engineering* — why do you need it? What is *Feature Cross* and *Bucketising*. What makes a bad/good ML model. Where would you perform feature engineering in a data pipeline. What is a good candidate for *Hyperparameter Tuning*.
- *Cloud AutoML*, and how to use prebuilt ML APIs like *Cloud Vision, Cloud Speech to Text, Cloud Natural Language, Cloud Translation and Cloud Video Intelligence.*

# **Streaming Systems with Pub/Sub, DataFlow**

- What are the 3 challenges of streaming: *Scalability & fault tolerant, latency, and instant insights as data arrives*. Understand how GCP services and architecture can meet these challenges for batch and streaming data pipeline.
- Learn to use *Pub/Sub* — creating a topic, creating a subscription, publishing a message, and subscribing to receive a message. Understand its place in the data pipeline architecture, and how it can be used for *Fan-In/Fan-Out*. Know the difference between *Push and Pull* and how it is implemented on Pub/Sub.
- How does *DataFlow* support *Windowing* — eg Fixed/Sliding/Sessions. Differentiate *Event Time vs Processing Time* in the context of data arrival latency. How to capture timestamp at message ingestion. How to create a DataFlow pipeline, apply windowing and perform aggregation techniques. Define *Watermark, Triggers, Transformations, Accumulation, Windowing*.

# **Serverless Data Analysis with Big Query**

- How to load/export data to/from *Big Query*, using the Console or via API tools. Know which file types are supported (CSV/JSON/AVRO/ORC/Parquet). Know which GCP services can be integrated and load data into Big Query.
- Learn the basics of SQL queries **with Big Query, including join on equality, join on boolean conditions, join on functions, join on window functions. Advanced capabilities using *With Structure, Array_Agg, Unnest*. What are *user defined functions (UDFs) and extended UDFs* (and their limitations).
- Know how to troubleshoot queries with the Big Query *explain plan*.

# **Serverless Data Storage with Big Table**

- Differentiate the use case scenarios between *Big Table* and *Cloud Data Store*.
- Understand the need to have a *good row key design* for Big Table (and what to avoid), especially with time ranged data.
- Have an idea of some good *performance tips* for using Big Table, and *scaling resources*.

# **Serverless Data Pipelines with DataFlow**

- How to create an *ETL pipeline*, parallel do, how to write/read to/from GCP storage services, running a pipeline job on GCP. Know the API options for Apache Beam with Java and Python
- How to perform *MapReduce* operations using Dataflow, using *GroupByKey* and *Combine* operations.
- What is *SideInputs* and how are they used.
- What is *DataPrep* used and how it is used together with DataFlow.

# **Unstructured Data with DataProc**

- General knowledge of the main *Hadoop* components — *Hive, Spark, Pig, HDFS, MapReduce, RDDs*. Know what is a Master, Worker and Preemptible Worker node.
- How Google Cloud Storage can be used for persistence.
- Have an idea of the general configuration options for launching and creating a *DataProc cluster* on GCP.
- How to customise clusters with initialisation scripts.

# **Data Analysis & Visualisation**

- How is *DataLab* used with Python to analyse data over BigQuery and Cloud Storage. How to manipulate data over Pandas Dataframe.
- How to query and create visualisations using *Data Studio* over various GCP services like Big Query, YouTube analytics etc