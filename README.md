# aws-journey

Udemy course: https://www.udemy.com/course/aws-fundamentals/

## Lesson 1: IAM

- **User:** An individual with AWS access.
- **User Group:** A collection of users with the same permissions.
- **Role:** Temporary permissions that can be assumed when needed.
- **Policy:** Defines permissions for AWS actions.

## Lesson 2: Compute Services

###1. EC2: Elastic Compute Cloud
* **Definition:** Virtual servers in the cloud to run applications and websites.
* **Example:** Start an EC2 instance to host a website or run an app.

**Auto Scaling**
* **Launch Template:** Template for launching EC2 instances.
* **Auto Scaling Group:** Adjusts EC2 instances based on demand.

**Load Balancing**
* **Target Group:** EC2 instances (or Auto Scaling Group) receiving traffic from the Load Balancer.
* **Load Balancer:** Distributes incoming traffic to EC2 instances.

###2. Elastic Beanstalk
* **Definition:** Elastic Beanstalk automates EC2 deployment, scaling, and load balancing. Just upload your code, and it handles everything, saving time and effort.

###3. Lambda
* **Definition:** A serverless compute service that runs code in response to events.
* **Example:** Upload a file to S3, and Lambda prints "New file was added to the S3" every time a file is added.
* **Note:** Ensure the Lambda function has an IAM role configured with the necessary access rights to interact with S3.

## Lesson 3: Storage Services

### S3: Simple Storage Service
* **Definition:** Cloud storage for storing and retrieving data.
* **When to Use:** For static content and backup storage.

### S3 Glacier
* **Definition:** Low-cost archival storage for infrequently accessed data.
* **When to Use:** For data that rarely needs access.

### EBS: Elastic Block Store
* **Definition:** Persistent block-level storage attached to EC2 instances.
* **When to Use:** For fast, low-latency storage for a single instance.

### EFS: Elastic File System
* **Definition:** Scalable, shared file storage for EC2 instances.
* **When to Use:** For shared file storage across multiple instances.
