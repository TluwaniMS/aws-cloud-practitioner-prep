# Storage Technology and Services

## AWS EBS (Elastic Block Store)

Amazon Elastic Block Store is a block storage service provided by Amazon Web Services (AWS) that allows users to create persistent block storage volumes and attach them to Amazon EC2 instances.
EBS volumes are highly available and reliable storage volumes that can be used as primary storage for data-intensive workloads such as databases, file systems, and application hosting. 

## AWS EFS (Elastic File System)

AWS EFS is a scalable, fully managed file storage service provided by Amazon Web Services (AWS).
Unlike Amazon EBS, which provides block storage, Amazon EFS provides file storage, making it suitable for use cases that require shared access to files between multiple Amazon EC2 instances or other AWS services.

## AWS Instance Store

AWS Instance Store,is a type of temporary block storage provided by Amazon Web Services (AWS) for Amazon EC2 instances. Instance store volumes are physically attached to the host server that hosts the EC2 instance and provide temporary block-level storage that persists only for the duration of the instance's life cycle. Once the instance is terminated, the data stored on the instance store volumes is lost.

## AWS S3(Simple Storage Service)

AWS S3, is a highly scalable and durable object storage service provided by Amazon Web Services (AWS). It is designed to store and retrieve any amount of data from anywhere on the web. S3 is commonly used for a wide range of use cases, including data storage for websites, application data, backup and recovery, big data analytics, content distribution, and archiving.

## AWS S3 Storage Classes.

* #### Standard:

Designed for general-purpose storage of frequently accessed data. It offers high availability, durability, and low latency.

* #### Standard-IA (Infrequent Access):	

Similar to the Standard class but intended for data that is accessed less frequently, with slightly lower storage costs but higher retrieval costs compared to Standard.

* #### One Zone-IA:

This is a variation of the Standard-IA storage class where data is stored redundantly within a single AWS Availability Zone instead of across multiple zones.

* #### Intelligent-Tiering:

This storage class is designed for data with unknown or changing access patterns. 
It automatically moves objects between two access tiers (frequent access and infrequent access) based on their usage patterns, optimizing costs without sacrificing performance or availability.

* #### Glacier:

This is a low-cost storage class designed for long-term archiving of data that is accessed infrequently.

* #### Glacier Deep Archive:

This is the lowest-cost storage class in S3, optimized for long-term data retention and archival with very infrequent access.

* #### Outposts:

This storage class is designed for storing data on AWS Outposts, which are fully managed and configurable compute and storage racks built with AWS-designed hardware. It extends AWS infrastructure, services, APIs, and tools to customer premises, enabling a truly consistent hybrid experience.

## AWS FSx

Amazon FSx for Windows File Server delivers fully managed Microsoft Windows file servers supported by a native Windows file system.
