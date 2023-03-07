# **FACT FINDING EXERCISE**

## 1) What is Configuration Orchestration?
Configuration Orchestration is the automated process of managing and coordinating the configuration of multiple systems and applications using tools that ensure consistency and efficiency.
Popular configuration orchestration tools include Ansible, Puppet, Chef, and SaltStack.
## 2) What is Configuration Management? List some commonly used tools for Configuration Management.
Configuration Management is the practice of systematically managing and maintaining the configuration of software, hardware, and systems throughout their lifecycle, from development to production. It involves identifying, documenting, controlling, and verifying changes to configurations, ensuring consistency and stability, and minimizing downtime and errors.

Some commonly used tools for Configuration Management are:

- Ansible: An open-source tool that uses YAML language to automate IT infrastructure and application deployment.
- Puppet: A tool that uses declarative language to manage configurations and automate the deployment of applications and infrastructure.
- Chef: A configuration management tool that uses a domain-specific language to define and automate configurations.
- SaltStack: A tool that uses a simple programming language to automate the configuration and deployment of infrastructure and applications.
- Terraform: An infrastructure as code (IAC) tool that automates the deployment and management of cloud infrastructure resources.
- Kubernetes: An open-source container orchestration platform that automates the deployment and scaling of containerized applications.

These tools allow organizations to manage and automate their configurations, making it easier to deploy applications, maintain consistency, and manage changes in a controlled and efficient manner.
## 3) What is Continuous Integration?
Continuous Integration (CI) is a software development practice that involves regularly integrating code changes into a shared repository, and automatically building, testing, and verifying those changes to ensure that they do not introduce errors or conflicts.

The process of continuous integration typically involves developers working on a feature or bug fix in a separate branch of the codebase. Once the changes are complete, the code is merged into the main branch, triggering an automated build and testing process. This process includes compiling the code, running automated tests, and checking for any issues that may have been introduced by the changes.

The goal of continuous integration is to catch errors and conflicts early in the development process, before they become more difficult and costly to fix. By automating the build and testing process, developers can quickly identify and fix issues, and ensure that the code is always in a working state.

Continuous Integration is often combined with other software development practices such as Continuous Delivery (CD) and Continuous Deployment (CDE) to create a streamlined software development pipeline that enables teams to quickly and safely release high-quality software.
## 4) What is Continuous delivery?
Continuous Delivery (CD) is a software development practice that involves automatically building, testing, and deploying code changes to production environments in a rapid and frequent manner.

The goal of continuous delivery is to enable software development teams to release software quickly and reliably, without sacrificing quality or stability. The process of continuous delivery typically involves automating the entire software delivery process, from code changes to production deployment.

In a continuous delivery pipeline, code changes are automatically built and tested in a staging environment, and if the tests are successful, the changes are automatically deployed to production. This allows teams to release new features and fixes quickly and safely, with minimal risk of downtime or errors.

Continuous delivery requires a high level of automation and collaboration across the entire software development lifecycle, including development, testing, and operations teams. It also requires robust testing and monitoring processes to ensure that changes are thoroughly tested and any issues are quickly identified and resolved.

Continuous delivery is often combined with other software development practices such as Continuous Integration (CI) and Continuous Deployment (CD) to create a streamlined software development pipeline that enables teams to quickly and safely release high-quality software.
## 5) What is AWS CloudFormation? List 3 advantages of Cloud Formation.
AWS CloudFormation is a service provided by Amazon Web Services that allows users to define and deploy infrastructure as code using templates. CloudFormation templates are written in JSON or YAML format and can be used to deploy a wide range of AWS resources, including EC2 instances, RDS databases, S3 buckets, and more.

Three advantages of AWS CloudFormation are:

- Infrastructure as Code: CloudFormation allows users to define and manage their infrastructure as code, which enables consistent and repeatable deployments. This approach also allows for version control, testing, and collaboration among teams.

- Automated Provisioning: CloudFormation automates the provisioning of resources, which helps to reduce the time and effort required to deploy complex infrastructure. This automation also reduces the risk of errors and misconfigurations that can occur during manual deployments.

- Cost Optimization: With CloudFormation, users can define and manage their infrastructure in a way that optimizes costs. For example, templates can be designed to scale resources up and down automatically based on demand, reducing the need for overprovisioning and minimizing waste.

Overall, AWS CloudFormation provides users with a powerful tool for managing their infrastructure as code, automating deployments, and optimizing costs.
## 6) What is JSON and YAML? List out 3 differences between them.
JSON (JavaScript Object Notation) and YAML (YAML Ain't Markup Language) are two popular data serialization formats used for exchanging data between different applications.

Here are three key differences between JSON and YAML:

- Syntax: JSON uses a more rigid syntax than YAML. JSON requires the use of specific key-value pairs and brackets to define objects, while YAML uses whitespace and indentation to define objects.

- Readability: YAML is often considered to be more human-readable than JSON, as its syntax is designed to be easy to read and write. YAML also supports comments, making it easier to document complex configurations.

- Compatibility: JSON is widely supported by a variety of programming languages and frameworks, making it a popular choice for web applications and APIs. While YAML is also supported by many programming languages, it is less widely used than JSON and may require additional configuration or libraries in some cases.

In summary, JSON and YAML are both useful data serialization formats, but differ in their syntax, readability, and compatibility with different programming languages and frameworks.

## 7) What is a stack in AWS CloudFormation?
In AWS CloudFormation, a stack is a collection of AWS resources that are created and managed as a single unit. Stacks can include any AWS resource that is supported by CloudFormation, such as EC2 instances, RDS databases, S3 buckets, and more.

A stack is defined using a CloudFormation template, which specifies the resources to be created and their configuration. When a stack is created, CloudFormation automatically provisions the necessary resources and manages their lifecycle, including updates, deletion, and rollback.

Stacks can be created, updated, or deleted using the AWS Management Console, the AWS Command Line Interface (CLI), or the CloudFormation API. CloudFormation also provides tools for monitoring and managing stacks, including the ability to view stack events, create or delete stacks, and set up automatic rollback in case of errors.

Using stacks in CloudFormation provides several benefits, including:

- Consistency and Repeatability: Stacks allow resources to be created and managed in a consistent and repeatable manner, which helps to ensure that the infrastructure is reliable and up-to-date.

- Scalability and Flexibility: Stacks can be easily scaled up or down as needed, allowing resources to be added or removed as demand changes.

- Cost Optimization: By managing resources as a single unit, stacks can be optimized for cost, reducing the risk of overprovisioning and minimizing waste.

Overall, stacks are a powerful tool for managing AWS resources in a consistent and scalable manner, and are an essential part of the AWS CloudFormation service.