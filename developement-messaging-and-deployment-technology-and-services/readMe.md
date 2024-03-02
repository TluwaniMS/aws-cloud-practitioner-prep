# Development, Messaging, and Deployment Technology and Services

## AWS Development tools:

* #### AWS CodeCommit

AWS CodeCommit is a fully-managed source control service provided by Amazon Web Services (AWS)

* #### AWS CodeBuild

AWS CodeBuild is a fully managed continuous integration service provided by Amazon Web Services (AWS). It automates the process of compiling source code, running tests, and producing deployable artifacts.

* #### AWS Codedeploy

AWS CodeDeploy is a fully managed deployment service provided by Amazon Web Services (AWS). It automates the process of deploying applications to a variety of compute services such as Amazon EC2 instances, AWS Lambda functions, and on-premises servers.

* #### AWS CodePipeline

AWS CodePipeline is a continuous integration and continuous delivery (CI/CD) service provided by Amazon Web Services (AWS). It automates the build, test, and deployment phases of the software release process, enabling developers to deliver updates to their applications rapidly and reliably.

## AWS CodeArtifact

AWS CodeArtifact is a fully managed software artifact repository service provided by Amazon Web Services (AWS). It enables developers to securely store, share, and manage software packages and dependencies used in their development and deployment workflows.

## AWS SNS (Simple Notification Service)

Amazon Simple Notification Service (Amazon SNS) is a fully managed messaging service provided by Amazon Web Services (AWS). It enables you to send messages or notifications to a large number of subscribers, including individuals, devices, and other distributed services.

## AWS SQS (Simple Queue Service)

Amazon Simple Queue Service (Amazon SQS) is another managed messaging service provided by Amazon Web Services (AWS). It offers a scalable, reliable, and fully managed message queuing service for sending, storing, and receiving messages between software components in a distributed system.

* #### Standard Que:

The Standard Queue in Amazon SQS offers a best-effort ordering of messages, meaning it attempts to maintain the order in which messages are sent, but occasional out-of-order delivery may occur. This queue type is optimized for high throughput, enabling you to send a large number of messages per second.

* #### FIFO Que:

The FIFO Queue ensures exactly-once processing and preserves the order of messages as they're sent and received. This means that messages are delivered in the same order they're sent and processed only once by the consumer. FIFO queues prioritize strict message ordering over throughput, resulting in a lower message processing rate compared to standard queues. 

* #### Short Polling:

Short polling is the default method used by SQS clients to retrieve messages from a queue. When a client sends a request to receive messages from a queue using short polling, the SQS service immediately responds with any available messages that are currently in the queue, up to a maximum of 10 messages per request. If there are no messages available in the queue at the time of the request, SQS returns an empty response. 

`In simple terms`

Short polling is like this frequent checking. You ask the mailbox (SQS queue) if there are any messages, and if there are, you get them immediately. If not, you keep asking frequently.

* #### Long Polling:

Long polling is an alternative method that SQS clients can use to retrieve messages from a queue. When a client sends a long polling request to receive messages from a queue, the SQS service holds the connection open for a specified period (between 1 and 20 seconds) to wait for messages to become available in the queue. If messages are available within the specified wait time, SQS immediately returns them to the client in the response. If no messages are available during the wait time, SQS extends the connection until a message becomes available or until the maximum long polling duration is reached. 

`In simple terms`

Long polling is like this patient waiting. You ask the mailbox if there are messages, but if there aren't any, you wait patiently for a set time. If a letter arrives during that time, you get it immediately. If not, you check again after some time.

In short, short polling checks frequently, while long polling waits patiently for messages to arrive, reducing the number of times you need to ask if there are messages, which can be more efficient in some situations.

## AWS SES(Simple Email Service)

Amazon Simple Email Service (Amazon SES) is a scalable and cost-effective email service provided by Amazon Web Services (AWS). It allows you to send and receive emails using the AWS infrastructure, making it easier to integrate email functionality into your applications and systems.

## AWS EventBridge

Amazon EventBridge is a fully managed event bus service provided by Amazon Web Services (AWS). It enables you to build event-driven architectures by integrating and routing events from various AWS services, third-party SaaS applications, and custom applications.

## AWS Step Functions

AWS Step Functions is a fully managed service provided by Amazon Web Services (AWS) that allows you to coordinate and orchestrate the execution of multiple AWS services and custom actions as workflows or state machines. It enables you to build complex, scalable, and resilient workflows by defining a series of steps or states and their transitions.

## AWS CLoudFormation

AWS CloudFormation is a service provided by Amazon Web Services (AWS) that allows you to define and manage your AWS infrastructure as code. It enables you to create, update, and delete AWS resources in a repeatable and automated manner by using templates written in either JSON or YAML format.

## AWS Elastic Beanstalk

AWS Elastic Beanstalk is a platform-as-a-service (PaaS) offering from Amazon Web Services (AWS) that simplifies the deployment, management, and scaling of web applications and services. It allows developers to quickly deploy applications without worrying about the underlying infrastructure setup.

## AWS X-ray

AWS X-Ray is a service provided by Amazon Web Services (AWS) that helps developers analyze and debug distributed applications, such as microservices-based architectures, by providing insights into how requests are processed and where bottlenecks or errors occur.