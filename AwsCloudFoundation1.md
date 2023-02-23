# AWS Cloud Foundation

  ## 1. Define what IaaS,PaaS and SaaS is?
     IaaS, PaaS, and SaaS are three different models of cloud computing services that provide various levels of infrastructure, platform, and software capabilities to users.
    
    Infrastructure as a Service (IaaS): 
     IaaS provides users with access to computing infrastructure such as virtual machines, servers, storage, and networking resources. IaaS providers offer scalable, on-demand resources that can be quickly provisioned and de-provisioned as needed. Examples of IaaS providers include Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

    Platform as a Service (PaaS): 
    PaaS provides users with a platform to build, deploy, and manage applications without having to manage the underlying infrastructure. PaaS providers offer an environment for developers to build, test, and deploy their applications quickly and easily. Examples of PaaS providers include Heroku, Google App Engine, and Microsoft Azure App Service.

    Software as a Service (SaaS): 
      SaaS provides users with access to software applications that are hosted and managed by a third-party provider. SaaS providers offer a wide range of applications such as email, customer relationship management (CRM), and project management tools. Users can access these applications through a web browser or mobile app, without having to manage the underlying infrastructure or software. Examples of SaaS providers include Salesforce, Dropbox, and Office 365.

    Each of these cloud computing models offers a different level of abstraction, and users can choose the model that best suits their needs

## 2.Provide 6 advantages of cloud computing?
    There are several advantages of cloud computing, some of which include:

    Scalability: 
      Cloud computing services can quickly scale up or down to meet changing demands, allowing businesses to avoid overprovisioning or underprovisioning resources. This means that businesses can save money by only paying for the resources they need.

    Flexibility: 
      Cloud computing services can be accessed from anywhere, as long as there is an internet connection. This means that businesses can provide their employees with access to the tools they need to work from home or on the go.

    Cost-effectiveness: 
      Cloud computing services can save businesses money on hardware, software, and infrastructure costs. With cloud computing, businesses can avoid the costs associated with purchasing, maintaining, and upgrading hardware and software.

    Disaster recovery: 
       Cloud computing services often include disaster recovery and backup features that can help businesses quickly recover from a disaster or data loss event.

    Collaboration: 
       Cloud computing services can facilitate collaboration among team members by allowing them to work on the same documents or projects in real-time.

    Security: 
      Cloud computing services often include security features that can help businesses protect their data and applications from unauthorized access, hacking, and other security threats. Cloud providers typically invest in security measures such as firewalls, encryption, and multi-factor authentication to keep data secure.
  

## 3)Define what an AWS region and an Availability Zone is?
     AWS region:
       It is a physical location around the world where AWS has one or more data centers. Each AWS region consists of multiple Availability Zones that are geographically isolated from each other. AWS currently has 25 regions globally, with multiple Availability Zones in each region.

    Availability Zone (AZ):
       It is an isolated location within an AWS region that is designed to be highly available and fault-tolerant. Each Availability Zone is housed in one or more data centers, with redundant power, networking, and connectivity. Availability Zones are connected to each other within a region through low-latency links, enabling applications to be designed for high availability and reliability. Each Availability Zone is independent of other Availability Zones in the same region, so they are designed to be isolated from failures in other Availability Zones. By deploying applications across multiple Availability Zones within a region, customers can achieve high availability, fault tolerance, and disaster recovery.

## 4)List all the AWS regions?
       
    * US East (Ohio)    us-east-2
    * US East (N. Virginia)    us-east-1
    * US West (N. California)    us-west-1
    * US West (Oregon)    us-west-2
    * Africa (Cape Town)    af-south-1
    * Asia Pacific (Hong Kong)    ap-east-1
    * Asia Pacific (Hyderabad)    ap-south-2    
    * Asia Pacific (Jakarta) ap-southeast-3    
    * Asia Pacific (Melbourne) ap-southeast-4    
    * Asia Pacific (Mumbai)    ap-south-1    
    * Asia Pacific (Osaka)    ap-northeast-3    
    * Asia Pacific (Seoul)    ap-northeast-2    
    * Asia Pacific (Singapore)    ap-southeast-1    
    * Asia Pacific (Sydney)    ap-southeast-2    
    * Asia Pacific (Tokyo)    ap-northeast-1    
    * Canada (Central)    ca-central-1     Europe (Frankfurt)    eu-central-1    
    * Europe (Ireland)    eu-west-1    
    * Europe (London)    eu-west-2    Europe (Milan)    eu-south-1    
    * Europe (Paris)    eu-west-3    
    * Europe (Spain)    eu-south-2    
    * Europe (Stockholm)    eu-north-1     Europe (Zurich)    eu-central-2        
    * Middle East (Bahrain)    me-south-1    
    * Middle East (UAE)    me-central-1        
    * South America (São Paulo)    sa-east-1    
    * AWS GovCloud (US-East)    us-gov-east-1    
    * AWS GovCloud (US-West)    us-gov-west-1
## 5)What are the categories in which the AWS services are grouped?
    AWS services are grouped into several categories based on their functionality, which include:
      Compute: 
       This category includes services for running and managing computing resources, such as virtual machines, containers, and serverless functions. Examples of AWS compute services include Amazon EC2, Amazon Elastic Container Service (ECS), and AWS Lambda.

    Storage: 
       This category includes services for storing and managing data, such as files, databases, and backups. Examples of AWS storage services include Amazon S3, Amazon EBS, and Amazon Glacier.

     Database: 
       This category includes services for managing structured and unstructured data, such as relational databases, NoSQL databases, and data warehouses. Examples of AWS database services include Amazon RDS, Amazon DynamoDB, and Amazon Redshift.

     Networking:
       This category includes services for managing network resources, such as virtual private clouds (VPCs), load balancers, and domain name system (DNS) services. Examples of AWS networking services include Amazon VPC, Amazon Route 53, and Elastic Load Balancing.

     Analytics: 
      This category includes services for analyzing and processing data, such as big data processing, business intelligence, and machine learning. Examples of AWS analytics services include Amazon EMR, Amazon Athena, and Amazon SageMaker.

     Security: 
       This category includes services for securing data and applications, such as identity and access management (IAM), encryption, and threat detection. Examples of AWS security services include AWS Identity and Access Management (IAM), AWS Key Management Service (KMS), and Amazon GuardDuty.

    Management and Governance: 
       This category includes services for managing and governing AWS resources, such as monitoring, logging, and cost management. Examples of AWS management and governance services include AWS CloudFormation, AWS CloudTrail, and AWS Cost Explorer.

    Application Integration: 
       This category includes services for integrating AWS services with other applications and services, such as messaging, queuing, and notification services. Examples of AWS application integration services include Amazon SNS, Amazon SQS, and AWS Step Functions.
     
## 6)What is the difference between object storage and block storage?
    Object storage is best used for large amounts of unstructured data, especially when durability, unlimited storage, scalability, and complex metadata management are relevant factors for overall performance. Block storage provides low latency and high-performance values in various use cases.



## 7. List two AWS compute services and explain them.
   #### AWS Lambda:
       lets you run code without provisioning or managing servers. You pay only for the compute time you consume—there is no charge when your code is not running.With Lambda, you can run code for virtually any type of application or backend service—all with zero administration. Just upload your code, and Lambda takes care of everything required to run and scale your code with high availability. You can set up your code to automatically trigger from other AWS services,or you can call it directly from any web or mobile app. 
   #### Amazon EC2:
      Auto Scaling helps you maintain application availability and allows you to automatically add or remove EC2 instances according to conditions you define.You can use the fleet management features of Amazon EC2 Auto Scaling to maintain the health and availability of your fleet. You can also use the dynamic and predictive scaling features of Amazon EC2 Auto Scaling to add or remove EC2 instances. Dynamic scaling responds to changing demand and predictive scaling automatically schedules theright number of EC2 instances based on predicted demand. Dynamic scaling and predictive scaling can be used together to scale faster.
## 8)List two AWS storage services and explain them?
     Here are two AWS storage services along with their brief explanation:
     Amazon S3 (Simple Storage Service):
       Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. It allows users to store and retrieve any amount of data from anywhere on the web. Amazon S3 provides unlimited storage with high durability, so users can store and retrieve data at any time with low latency. It is also highly secure, providing features like encryption, access control, and compliance with regulatory standards. Amazon S3 is used by millions of customers for a wide range of use cases such as backup and archiving, big data analytics, and content distribution.

    Amazon EBS (Elastic Block Store): 
       Amazon EBS is a block storage service that provides persistent storage for use with Amazon EC2 instances. It is designed for workloads that require frequent and fast access to data. Amazon EBS volumes are highly available and can be replicated across Availability Zones for increased durability. Amazon EBS supports multiple volume types, including SSD and HDD, to meet different performance and cost requirements. Amazon EBS volumes can also be backed up and restored to protect against data loss or corruption. Amazon EBS is commonly used for a variety of use cases such as database storage, file systems, and container storage.