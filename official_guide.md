# Official guide

### **Section 1. Designing data processing systems**

1.1 Selecting the appropriate storage technologies. Considerations include:

a. Mapping storage systems to business requirements

b. Data modeling

c. Trade-offs involving latency, throughput, transactions

d. Distributed systems

e. Schema design

1.2 Designing data pipelines. Considerations include:

a. Data publishing and visualization (e.g., BigQuery)

b. Batch and streaming data (e.g., Dataflow, Dataproc, Apache Beam, Apache Spark and Hadoop ecosystem, Pub/Sub, Apache Kafka)

c. Online (interactive) vs. batch predictions

d. Job automation and orchestration (e.g., Cloud Composer)

1.3 Designing a data processing solution. Considerations include:

a. Choice of infrastructure

b. System availability and fault tolerance

c. Use of distributed systems

d. Capacity planning

e. Hybrid cloud and edge computing

f. Architecture options (e.g., message brokers, message queues, middleware, service-oriented architecture, serverless functions)

g. At least once, in-order, and exactly once, etc., event processing

1.4 Migrating data warehousing and data processing. Considerations include:

a. Awareness of current state and how to migrate a design to a future state

b. Migrating from on-premises to cloud (Data Transfer Service, Transfer Appliance, Cloud Networking)

c. Validating a migration

### **Section 2. Building and operationalizing data processing systems**

2.1 Building and operationalizing storage systems. Considerations include:

a. Effective use of managed services (Cloud Bigtable, Cloud Spanner, Cloud SQL, BigQuery, Cloud Storage, Datastore, Memorystore)

b. Storage costs and performance

c. Life cycle management of data

2.2 Building and operationalizing pipelines. Considerations include:

a. Data cleansing

b. Batch and streaming

c. Transformation

d. Data acquisition and import

e. Integrating with new data sources

2.3 Building and operationalizing processing infrastructure. Considerations include:

a. Provisioning resources

b. Monitoring pipelines

c. Adjusting pipelines

d. Testing and quality control

### **Section 3. Operationalizing machine learning models**

3.1 Leveraging pre-built ML models as a service. Considerations include:

a. ML APIs (e.g., Vision API, Speech API)

b. Customizing ML APIs (e.g., AutoML Vision, Auto ML text)

c. Conversational experiences (e.g., Dialogflow)

3.2 Deploying an ML pipeline. Considerations include:

a. Ingesting appropriate data

b. Retraining of machine learning models (AI Platform Prediction and Training, BigQuery ML, Kubeflow, Spark ML)

c. Continuous evaluation

3.3 Choosing the appropriate training and serving infrastructure. Considerations include:

a. Distributed vs. single machine

b. Use of edge compute

c. Hardware accelerators (e.g., GPU, TPU)

3.4 Measuring, monitoring, and troubleshooting machine learning models. Considerations include:

a. Machine learning terminology (e.g., features, labels, models, regression, classification, recommendation, supervised and unsupervised learning, evaluation metrics)

b. Impact of dependencies of machine learning models

c. Common sources of error (e.g., assumptions about data)

### **Section4. Ensuring solution quality**

4.1 Designing for security and compliance. Considerations include:

a. Identity and access management (e.g., Cloud IAM)

b. Data security (encryption, key management)

c. Ensuring privacy (e.g., Data Loss Prevention API)

d. Legal compliance (e.g., Health Insurance Portability and Accountability Act (HIPAA), Children's Online Privacy Protection Act (COPPA), FedRAMP, General Data Protection Regulation (GDPR))

4.2 Ensuring scalability and efficiency. Considerations include:

a. Building and running test suites

b. Pipeline monitoring (e.g., Cloud Monitoring)

c. Assessing, troubleshooting, and improving data representations and data processing infrastructure

d. Resizing and autoscaling resources

4.3 Ensuring reliability and fidelity. Considerations include:

a. Performing data preparation and quality control (e.g., Dataprep)

b. Verification and monitoring

c. Planning, executing, and stress testing data recovery (fault tolerance, rerunning failed jobs, performing retrospective re-analysis)

d. Choosing between ACID, idempotent, eventually consistent requirements

4.4 Ensuring flexibility and portability. Considerations include:

a. Mapping to current and future business requirements

b. Designing for data and application portability (e.g., multicloud, data residency requirements)

c. Data staging, cataloging, and discovery