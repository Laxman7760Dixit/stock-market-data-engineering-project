# Stock Market Kafka Real Time Data Engineering Project

In this project, you will execute an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.

We are going to use different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.


# Introduction to Kafka

Apache Kafka is an open-source distributed streaming platform which is designed to handle high volumes of data in real-time, making it an ideal platform for building real-time data pipelines, streaming applications, and event-driven architectures.


Real-time Data Pipelines

One of the most common use cases for Kafka is building real-time data pipelines. For example, Kafka can be used to collect data from sensors, log files, social media platforms, and other sources, and stream it to data warehouses, machine learning platforms, and other destinations.

#Messaging Systems

Kafka can also be used as a messaging system, allowing for fast and efficient message delivery between applications and services. For example, Kafka can be used to power chat applications, email systems, and other real-time communication systems.
Stream Processing

Kafka’s support for stream processing frameworks like Apache Flink and Apache Spark Streaming allows for real-time data processing and analysis. For example, Kafka can be used to build real-time fraud detection systems, real-time recommendation engines, and real-time sentiment analysis systems.

#Event-driven Architecture

Kafka’s support for event-driven architecture makes it an ideal choice for building complex, event-driven applications. With Kafka, events can be produced, consumed, and processed in real-time. For example, Kafka can be used to build event-driven microservices architectures, IoT platforms, and other event-driven systems.

#Log Aggregation

Kafka can also be used for log aggregation, allowing for the collection, storage, and analysis of logs from multiple sources. For example, Kafka can be used to collect and analyze logs from web servers, databases, and other systems.

![image](https://github.com/Laxman7760Dixit/stock-market-data-engineering-project/assets/94826932/e777c7bc-7779-4a2e-8b5b-a546cc203aa3)


#Kafka Topic:

A Topic is a logical name for a stream of data to which messages are published by producers and from which messages are consumed by consumers.

A Kafka topic is divided into one or more partitions, which are stored across a Kafka cluster.

#Broker:

A broker is a single instance of a Kafka server that stores and manages one or more Kafka partitions. A Kafka cluster consists of one or more brokers that work together to manage the storage and processing of Kafka topics.

#Producer & Consumer:

Producer produces data to a kafka topic. Producers can write data to topics in parallel, and Kafka ensures that the data is evenly distributed across partitions.

Consumer consumes data from one or more Kafka topics. Consumers subscribe to topics and read data from partitions. Kafka ensures that only one consumer from a group receives data from a partition at any given time.

#Partitions:

Kafka topics are divided into a number of partitions, which contains messages in an unchangeable sequence(immutable).
Each message in a partition is assigned and identified by its unique offset.
A topic can also have multiple partition logs.This allows for multiple consumers to read from a topic in parallel.

#Replication:

Replication is the process of creating multiple copies of data. Replication ensures that if a broker (node) fails or becomes unavailable, the data stored on that broker can be recovered from other brokers that have a copy of the same data.

#Kafka APIs

Kafka has four core APIs:

Producer API allows an application to publish a stream of records to one or more Kafka topics.

Consumer API allows an application to subscribe to one or more topics and process the stream of records.

Streams API allows an application to act as a stream processor, consuming an input stream from one or more topics and producing an output stream to one or more output topics, effectively transforming the input streams to output streams.

Connector API allows building and running reusable producers or consumers that connect Kafka topics to existing applications or data systems. For example, a connector to a relational database might capture every change to a table.


# Architecture

![Architecture](https://github.com/Laxman7760Dixit/stock-market-data-engineering-project/assets/94826932/f77d73ac-83ea-40b3-b26b-4c62cef52fe3)

# Technology Used

Programming Language - Python

Amazon Web Service (AWS)

S3 (Simple Storage Service)

Athena

Glue Crawler

Glue Catalog

EC2

Apache Kafka


