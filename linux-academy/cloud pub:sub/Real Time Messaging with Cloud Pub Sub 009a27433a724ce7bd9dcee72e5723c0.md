# Real Time Messaging with Cloud Pub/Sub

# What is streaming data

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled.png)

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled%201.png)

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled%202.png)

# Overview

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled%203.png)

## How it works?

**Terminology -** topics, messages, publishers, subscribers, message store

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled%204.png)

1. Publisher application creates a topic in the Cloud Pub/Sub service and send messages to that topic. A message contains a payload and optional attributes that describe the payload content
2. Messages are stored in a message storage until they are delivered and acknowledged by subscribers
3. Pub/Sub forwards messages from a topic to all subscribers individually. Messages can be either pushed by Pub/Sub to subscribers or pullded by subscribers from Pub/Sub 
4. A subscriber receives pending messages from its subscription and acknowledges each one to the Pub/Sub service
5. After message is acknowledged by the subscriber then it is removed from the subscription’s queue of messages

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled%205.png)

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled%206.png)

# Hands on

## Steps

1. Create a topic
2. Create a subscription
3. Publish a message
4. Retrieve messages

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled%207.png)

# Connect Kafka to GCP

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled%208.png)

# Monitoring Subscriber health

![Untitled](Real%20Time%20Messaging%20with%20Cloud%20Pub%20Sub%20009a27433a724ce7bd9dcee72e5723c0/Untitled%209.png)

1. Under provisioned mean that it simply doesnt have the compute power necessary to keep up - so for example when working with Cloud Dataflow, you