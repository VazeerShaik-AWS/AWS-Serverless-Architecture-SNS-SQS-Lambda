# Serverless Messaging using SNS, SQS & Lambda

## Overview

Designed a reliable and scalable serverless messaging system on AWS using SNS, SQS and Lambda to enable asynchronous communication and decoupled architecture.

## Objective

* Implement reliable asynchronous messaging
* Decouple producers and consumers
* Handle message failures gracefully
* Ensure scalability during traffic spikes

## Problem Statement

* Direct service-to-service communication leads to cascading failures
* Lack of buffering results in poor handling of traffic spikes
* Tight coupling reduces system flexibility and reliability

## Architecture

* Amazon SNS publishes messages from producers
* Amazon SQS queues buffer messages ensuring durability
* AWS Lambda processes messages asynchronously from the queue
* The system enables loose coupling and fault-tolerant message handling

## AWS Services Used

* Amazon SNS
* Amazon SQS
* AWS Lambda
* Amazon S3 

## Outcome / Business Impact

* Improved fault tolerance through decoupled architecture
* Reliable message delivery using queue-based buffering
* Scalable system capable of handling traffic spikes
* Production-ready asynchronous processing system

## Author

**Vazeer Shaik**

AWS Cloud Engineer

---

This project demonstrates hands-on expertise in serverless and event-driven architectures on AWS.
