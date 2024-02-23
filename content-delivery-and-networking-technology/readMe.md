# Content Delivery & Networking Technology and Service

## AWS CloudFront

AWS CloudFront is a content delivery network (CDN) service provided by Amazon Web Services (AWS). It helps deliver content, such as web pages, videos, images, and other static or dynamic files, to users with low latency and high data transfer speeds. CloudFront works by caching content at edge locations situated around the world, reducing the distance between users and the content they request.

## AWS Global Accelerator

AWS Global Accelerator is a networking service that improves the availability and performance of your applications for global users by routing traffic through the AWS global network infrastructure.

## AWS VPC (Virtual Private Cloud)

An AWS VPC, or Amazon Virtual Private Cloud, is a virtual network environment provided by Amazon Web Services (AWS). It allows you to launch AWS resources in a logically isolated section of the AWS Cloud. With a VPC, you can define your own virtual network topology, including IP address ranges, subnets, route tables, and network gateways.

* #### Subnet:

An AWS subnet, or Amazon Virtual Private Cloud (VPC) subnet, is a segmented portion of an AWS Virtual Private Cloud (VPC) network. In simpler terms, it's a range of IP addresses in your VPC where you can place AWS resources such as EC2 instances, RDS databases, and more.

* #### Gateway:

Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. It acts as a front door for applications to access data, business logic, or functionality from backend services, such as AWS Lambda functions or EC2 instances, or any publicly accessible web service.

* #### Route Table:

An AWS route table is a networking component within an Amazon Virtual Private Cloud (VPC) that defines how traffic should be routed between subnets, the internet, and other network destinations. Route tables are essentially sets of rules, called routes, that determine where network traffic is directed.

* #### Security group:

An AWS security group acts as a virtual firewall for your EC2 instances (virtual servers) to control inbound and outbound traffic. Essentially, it functions as a set of firewall rules that regulate the traffic flow to and from instances within a specific AWS region.

* #### Network Access Control List:

An AWS Network Access Control List (ACL) is a virtual firewall that controls traffic at the subnet level in an Amazon Virtual Private Cloud (VPC). While AWS security groups operate at the instance level (controlling traffic to and from individual instances), network ACLs operate at the subnet level (controlling traffic to and from all instances within a subnet).

## AWS Route53

Amazon Route 53 is a scalable and highly available Domain Name System (DNS) web service offered by Amazon Web Services (AWS). It is designed to route end users to internet applications by translating domain names (such as www.example.com) into numeric IP addresses (such as 192.0.2.1) that computers use to connect to each other.

## AWS Direct Connect

AWS Direct Connect is a cloud service provided by Amazon Web Services (AWS) that allows you to establish a dedicated network connection between your on-premises data center or office and AWS. It enables you to bypass the public internet and establish a private, high-bandwidth, low-latency connection to AWS services, which can be particularly beneficial for enterprises with high data transfer requirements, strict security and compliance needs, or latency-sensitive workloads.

## AWS VPN(Virtual Private Network)

AWS VPN is a service provided by Amazon Web Services (AWS) that enables you to establish secure connections between your on-premises network or data center and your Amazon Virtual Private Cloud (VPC) using encrypted tunnels over the internet. This allows you to extend your corporate network into the AWS cloud securely, facilitating hybrid cloud architectures and providing secure access to AWS resources.