# Security, Compliance and Governance

## The AWS Shared Responsibility Model

The AWS (Amazon Web Services) Shared Responsibility Model is a fundamental concept that outlines the division of responsibilities between AWS and its customers regarding security and compliance in the cloud. This model helps clarify who is responsible for what aspects of security and compliance when using AWS services. 

The model essentially divides responsibilities into two main categories:

#### AWS Responsibilities:

AWS is responsible for the security *of* the cloud. This includes:

* Physical security of the data centers, facilities, and infrastructure.
* Security of the hypervisor and virtualization infrastructure.
* Managed services such as Amazon S3, Amazon RDS, etc., including patching and maintenance.
* Global infrastructure security including networking, DDoS protection, and availability zones.

#### Customer Responsibilities:

Customers are responsible for security *in* the cloud. This includes:

* Data protection and encryption, both in transit and at rest.
* Identity and access management (IAM), including user access control and permissions management.
* Securing operating systems, applications, and configurations within AWS instances.
* Network and firewall configurations, including VPC (Virtual Private Cloud) settings.
* Compliance adherence based on industry standards and regulations applicable to the customer's use case.