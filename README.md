# aws-journey

Udemy course: https://www.udemy.com/course/aws-fundamentals/

## Lesson 1: IAM

### User:
- **Definition**: An individual with AWS access.
- **When to Use**: When you need to grant specific access to a person or application.

### User Group:
- **Definition**: A collection of users with the same permissions.
- **When to Use**: When you want to assign the same set of permissions to multiple users.

### Role:
- **Definition**: Temporary permissions that can be assumed when needed. Roles can be assigned to a user or an AWS service (like EC2).
- **When to Use**: When you need to grant temporary access to AWS resources, either to a user or an AWS service.

### Policy:
- **Definition**: A document that defines permissions for AWS resources.
- **When to Use**: To specify what actions are allowed or denied for users, groups, or roles.

---

## Lesson 2: Compute Services

### EC2 - Elastic Compute Cloud:
- **Definition**: Virtual servers in the cloud to run applications.
- **When to Use**: When you need full control over the server environment.

### Auto Scaling:
- **Definition**: Automatically adjusts the number of EC2 instances based on demand.
- **When to Use**: To scale your application based on traffic.

### Load Balancing:
- **Definition**: Distributes traffic across multiple EC2 instances.
- **When to Use**: To ensure high availability and efficient traffic distribution.

### Elastic Beanstalk:
- **Definition**: Automates EC2 deployment, scaling, and load balancing.
- **When to Use**: When you want to deploy and manage apps without handling the infrastructure.

### Lambda:
- **Definition**: Serverless compute that runs code in response to events.
- **When to Use**: For running code without managing servers (e.g., on file uploads).

---

## Lesson 3: Storage Services

### S3 - Simple Storage Service:
- **Definition**: Scalable cloud storage for objects like images, videos, and backups.
- **When to Use**: For static content and backup storage.

### S3 Glacier:
- **Definition**: Low-cost archival storage for infrequently accessed data.
- **When to Use**: For data that rarely needs access.

### EBS - Elastic Block Store:
- **Definition**: Persistent block-level storage attached to EC2 instances.
- **When to Use**: For fast, low-latency storage for a single instance.

### EFS - Elastic File System:
- **Definition**: Scalable, shared file storage for EC2 instances.
- **When to Use**: For shared file storage across multiple instances.

