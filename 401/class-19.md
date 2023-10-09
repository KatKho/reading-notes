# AWS: Events

## AWS SQS vs SNS

### What is the difference between SQS and SNS?
SQS (Simple Queue Service) is a message queuing service for decoupling components of an application, while SNS (Simple Notification Service) is a pub/sub messaging service for distributing messages to multiple subscribers.

### What are some use cases for both SNS and SQS?
Use cases for SNS:
- Sending alerts and notifications.
- Distributing updates to multiple subscribers.
- Triggering AWS Lambda functions.

Use cases for SQS:
- Decoupling components in a microservices architecture.
- Ensuring reliable message processing.
- Handling asynchronous and batch processing tasks.

## AWS SNS and SQS

### Describe how to use SQS and SNS in a “fanout” pattern.
In a fanout pattern, SNS acts as the fanout source and sends messages to multiple SQS queues, each serving as a subscriber. This enables broadcasting messages to multiple consumers simultaneously.

### Explain how “push notifications” work, using SNS.
With SNS push notifications, SNS sends messages directly to subscribers, such as mobile devices or HTTP endpoints. Subscribers register with SNS, and when a message is published, SNS pushes it to all registered subscribers, allowing immediate message delivery.

## SQS and SNS Basics

### How might a large-scale, distributed application make use of a Queue system like SQS?
In a large-scale, distributed application, SQS can be used to manage asynchronous communication between various microservices or components. It ensures reliable message delivery, load balancing, and decoupling, making it easier to handle spikes in traffic and maintain system reliability.

## Reflection

1. What are your learning goals after reading and reviewing the class README?
   - My learning goal is to retain a comprehensive understanding of the course topics and themes covered in the README so that I can revisit and reference them as needed.

## Things I Want to Know More About

## Reference

- Reading Materials
- ChatGPT