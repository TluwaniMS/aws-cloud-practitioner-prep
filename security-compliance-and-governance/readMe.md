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

## AWS IAM (Identity and Access Management) 

AWS IAM (Identity and Access Management) enables you to securely control access to AWS services and resources. IAM allows you to manage users, groups, roles, and their permissions within your AWS account. It provides centralized control over who can access specific AWS resources and what actions they can perform on those resources.

* #### Roles:

IAM roles are entities with permissions policies that determine what actions can be performed on which resources. Roles are not associated with a specific user or group; instead, they are assumed by users, applications, or AWS services temporarily. Roles are commonly used to delegate access to resources or services across AWS accounts.

* #### Policies:

IAM policies are JSON documents that define permissions and access control rules. Policies can be attached to users, groups, roles, or directly to AWS resources. They specify the actions allowed or denied, the resources those actions can be performed on, and conditions under which actions are allowed or denied.

* #### AWS Access Analyzer:

AWS Access Analyzer is a service provided by Amazon Web Services (AWS) that helps you analyze and identify unintended access to your AWS resources. It continuously monitors the configurations of your AWS resources and identifies any resources that are publicly accessible or shared with an AWS account outside of your organization. Access Analyzer evaluates resource policies, IAM policies, and S3 bucket policies to detect any potential security risks.

* #### AWS Policy Simulator:

The AWS Policy Simulator is a tool provided by Amazon Web Services (AWS) that allows you to simulate and test the effects of IAM policies and resource policies to understand their potential impact on access control within your AWS environment. It helps you evaluate and validate your policies before applying them to your production environment, ensuring that they provide the intended access permissions and do not inadvertently grant excessive privileges.

## AWS Identity Federation:

AWS Identity Federation is a feature provided by Amazon Web Services (AWS) that enables you to grant  access to AWS resources to users who authenticate through an external identity provider (IdP). This allows you to leverage existing authentication systems, such as corporate directories or social identity providers, to grant access to AWS resources without the need to create and manage AWS IAM (Identity and Access Management) users.

## AWS IAM Identity Center

AWS IAM Identity Center, formerly known as AWS Single Sign-On (SSO), is a cloud-based service offered by Amazon Web Services (AWS) that helps you centrally manage access to multiple AWS accounts and applications. It streamlines the process of providing users with access to the right AWS resources across your AWS organization.

## AWS Web Federated Identities

AWS Web Identity Federation is a feature provided by Amazon Web Services (AWS) that allows you to let users authenticate with a Web-based identity provider (like Amazon Cognito, Facebook, Google, or any other OpenID Connect-compatible identity provider), and then grant them temporary access to AWS resources. 