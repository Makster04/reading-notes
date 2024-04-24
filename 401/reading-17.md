# [Readings: AWS: S3 and Lambda](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-17)

## [AWS s3](https://aws.amazon.com/s3/)
1. **What is Amazon S3?**
* Amazon S3, or Amazon Simple Storage Service, is a scalable object storage service provided by Amazon Web Services (AWS). It allows users to store and retrieve any amount of data from anywhere on the web.
2. **Name some use cases for Amazon S3.**
* A) **Data Backup and Archiving:** S3 provides durable and highly available storage, making it suitable for backup and long-term data archiving.
* B) **Static Website Hosting:** S3 can host static websites by serving static web content directly to users.
* C) **Data Lakes:** S3 can serve as the foundation for building data lakes, storing structured and unstructured data for analytics purposes.
* D) **Content Distribution:** S3 integrates with AWS CloudFront to distribute content globally with low latency and high transfer speeds.
* E) **Application Data Storage:** Many applications use S3 as a storage backend for storing user-generated content, media files, and application data.
3. **Name some benefits of using Amazon S3.**
* A) **Scalability:** S3 can scale to accommodate any amount of data, from gigabytes to petabytes, without manual intervention.
* B) **Durability and Availability:** S3 offers 99.999999999% (11 nines) durability and 99.99% availability of objects over a given year.
* C) **Security:** S3 supports fine-grained access controls, encryption at rest and in transit, and integrates with AWS Identity and Access Management (IAM) for secure data access.
* D) **Cost-Effectiveness:** With S3's pay-as-you-go pricing model, users only pay for the storage they use, making it cost-effective for storing large amounts of data.

## [AWS Lambda Basics](https://www.serverless.com/aws-lambda)
1. **What is AWS Lambda?** 
* AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS) that allows users to run code without provisioning or managing servers. It executes code in response to events triggered by AWS services or custom events.
2. **Name some use cases for AWS Lambdas.**
* A) **Event-Driven Processing:** Lambdas are commonly used for event-driven processing, such as processing data from Amazon S3, DynamoDB streams, or Amazon Kinesis.
* B) **Real-Time File Processing:** Lambdas can be used to process files uploaded to S3, enabling real-time data processing and analysis.
* C) **API Backends:** Lambdas can power API endpoints, providing a scalable and cost-effective solution for building serverless APIs.
* D) **Data Transformation:** Lambdas can transform data between different formats or perform data enrichment tasks in real-time.
* E) **Scheduled Tasks:** Lambdas can be scheduled to run periodically, automating tasks such as data backups, cleanup, or report generation.
3. **Describe “serverless” to a non-technical friend.**
* "Serverless" doesn't mean there are no servers involved; rather, it means you don't have to worry about managing or provisioning servers yourself. Imagine you have a magical machine that appears whenever you need it, does the work you ask it to, and then disappears when it's done. That's what serverless is like. You focus on writing your code, and the cloud provider takes care of running it for you, without you needing to worry about the underlying infrastructure.


## [CDN](https://cyberhoot.com/cybrary/content-delivery-network-cdn/)
1. **What is a CDN?**
2. **How does a CDN work with relation to the website visitor?**
3. **What are the benefits of employing a CDN?**


## Reflections
1. **What are your learning goals after reading and reviewing the class [README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-17/)** 
The README sets learning objectives for cloud computing and AWS deployment, covering fundamental cloud concepts, Elastic Beanstalk deployment methods, cost management, and security practices. It emphasizes mastering deployment with Elastic Beanstalk, exploring additional AWS features like S3 and GitHub Actions, and developing troubleshooting skills while ensuring security in cloud deployments.

