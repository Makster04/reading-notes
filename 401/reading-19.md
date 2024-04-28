# [Readings: AWS: Events](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-19)

## [AWS API Gateway Overview](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)
1. **What is the difference betweeen SQS and SNS?**
* SQS: SQS provides a message queuing service where messages are stored in queues and processed by consumers at their own pace, ideal for asynchronous communication and workload decoupling.
* SNS: In contrast, SNS operates as a pub/sub messaging service, enabling real-time, push-based communication by publishing messages to topics and delivering them instantly to subscribers, making it suitable for event-driven architectures and push notifications.
2. **What are some use cases for both SNS and SQS?** SQS is used for asynchronous tasks, batch processing, and workload isolation in distributed systems. SNS facilitates event-driven architectures, push notifications, and broadcasting messages to multiple subscribers simultaneously.

## [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)
1. **Describe how to use SQS and SNS in a “fanout” pattern.**
*  In a fanout pattern, SNS publishes messages to a topic, which then distributes them to all subscribed SQS queues. This enables parallel processing and scaling across multiple downstream systems.
2. **Explain how “push notifications” work, using SNS.**
*  SNS delivers messages to endpoints like mobile devices or email addresses in real-time. When a message is published to a topic, SNS pushes it to all subscribed endpoints, triggering immediate display of notifications on devices without requiring active polling.

## [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)
1. **How might a large scale, distributed application make use of a Queue system like SQS?**
* In large-scale distributed applications, SQS enables asynchronous communication between components. It allows components to enqueue messages for processing by other parts of the system, promoting loose coupling and scalability while ensuring reliable message delivery even during peak loads or component failures.

## Bookmark and Review
* [SNS Javascript SDK](https://canvas.instructure.com/courses/8944808/discussion_topics/21361246/submit)
* [SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)
  
## Reflection
1. **What are your learning goals after reading and reviewing the class [README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-19/)?**
* My goal after reviewing the class README on AWS Events is to understand the differences between SNS and SQS, identify their use cases, grasp FIFO queue concepts, and master the publisher-subscriber relationship in SNS. Additionally, I aim to gain practical skills in implementing these concepts using AWS SDKs in Node.js, enabling me to effectively leverage AWS Events services in building scalable distributed systems.

## Things I want to know


