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