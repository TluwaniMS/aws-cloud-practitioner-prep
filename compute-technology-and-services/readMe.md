# Compute technology and services

## EC2 (Elastic Cloud Computing)

### What is EC2 ?

AWS EC2 stands for Amazon Elastic Compute Cloud. It is a web service provided by Amazon Web Services (AWS) that allows users to rent virtual servers, known as instances, on which they can run their own applications.

### EC2 Payment options:

* #### On-Demand Instances:

With on-demand instances, you pay for compute capacity by the hour or by the second with no long-term commitments or upfront payments.

* #### Reserved Instances (RI):

Reserved Instances allow you to reserve EC2 capacity for a one- or three-year term, which can result in significant cost savings compared to on-demand pricing, especially for steady-state workloads.

* #### Savings Plans:

AWS offers Savings Plans, which provide significant savings compared to on-demand prices in exchange for a commitment to a consistent amount of usage, measured in dollars per hour, for a one- or three-year term.

* #### Spot Instances:

Spot Instances allow you to bid for unused EC2 capacity at a significantly lower price compared to on-demand instances. However, the availability of spot instances is subject to fluctuations based on supply and demand, and your instances can be terminated with short notice if the spot price exceeds your bid or if the capacity becomes unavailable.

* #### Dedicated Hosts:

With Dedicated Hosts, you have exclusive access to physical servers dedicated to your use. Dedicated Hosts can help you meet compliance requirements or licensing restrictions that require a specific physical server.

### ELB (Elastic Load Balancing)

Amazon ELB (Elastic Load Balancing) Load Balancing refers to the process of distributing incoming application or network traffic across multiple EC2 instances in a cloud computing environment. It helps to improve the availability and fault tolerance of applications by spreading the load evenly across multiple instances. This ensures that no single instance becomes overwhelmed with requests, thus preventing downtime or degraded performance.

### EC2 Autoscaling

Amazon EC2 Auto Scaling is a service provided by AWS that helps automatically adjust the number of EC2 instances in a scalable manner based on demand. It is a key feature for ensuring that your application maintains performance and availability, even during varying levels of traffic or demand fluctuations.

##### Types of scaling:

* ##### Vertical Scaling (Scaling up):

Vertical scaling involves adding more resources (such as CPU, RAM, or storage) to an existing server or instance.This is typically done by upgrading the hardware specifications of the server, such as adding more CPU cores, increasing RAM capacity, or upgrading to a faster storage device.

* ##### Horizontal Scaling (Scaling Out):

Horizontal scaling involves adding more instances or servers to distribute the load across multiple machines.Instead of increasing the resources of individual servers, horizontal scaling adds more servers to the system, spreading the workload across them.

### AWS EC2 (Elastic Compute Cloud) Optimizer

AWS EC2 (Elastic Compute Cloud) Optimizer is a tool provided by Amazon Web Services (AWS) that helps optimize your EC2 instances for better performance and cost efficiency. It analyzes the resource utilization of your EC2 instances and provides recommendations to right-size your instances based on their actual usage patterns.

### AWS Elastic Container Service (ECS) 

Amazon Elastic Container Service (ECS) is a fully managed container orchestration service provided by Amazon Web Services (AWS). It allows you to easily run, manage, and scale containerized applications using Docker containers and enables you to deploy, manage, and scale containerized applications on a cluster of container instances.

### Amazon Elastic Kubernetes Service (EKS)

Amazon Elastic Kubernetes Service (EKS) is a managed Kubernetes service provided by Amazon Web Services (AWS).
AWS EKS allows you to run Kubernetes clusters on AWS infrastructure without needing to manage the underlying Kubernetes control plane.

## Serverless

### What is server less?

In cloud computing terms, "serverless" refers to a cloud computing model where the cloud provider dynamically manages the allocation and provisioning of servers and infrastructure resources, allowing developers to focus solely on writing and deploying code without the need to manage the underlying infrastructure.

### AWS Lambda

AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS) that allows you to run code without provisioning or managing servers. With Lambda, you can upload your code, and Lambda takes care of provisioning and managing the infrastructure needed to run that code in response to events.

### AWS Fargate

AWS Fargate is a serverless compute engine for containers offered by Amazon Web Services (AWS). It allows you to run containers without managing the underlying infrastructure. With Fargate, you can focus on building and deploying your containerized applications without needing to provision or manage servers or clusters.

### AWS Outpost

AWS Outposts is a fully managed service by Amazon Web Services (AWS) that extends AWS infrastructure, services, APIs, and tools to virtually any data center, co-location space, or on-premises facility. It enables customers to run AWS compute, storage, database, and other services locally, while seamlessly connecting to the broader range of AWS services available in the cloud.

### AWS Lightsail

AWS Lightsail is a simplified virtual private server (VPS) service offered by Amazon Web Services (AWS). It's designed to provide an easy-to-use platform for individuals, small businesses, and developers who need a low-cost, straightforward way to launch and manage cloud instances without the complexity of traditional AWS services.