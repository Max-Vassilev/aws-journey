# aws-journey

Udemy course: [AWS Fundamentals](https://www.udemy.com/course/aws-fundamentals/)

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

1. **Auto Scaling**:
   - **Definition**: Automatically adjusts the number of EC2 instances based on demand.
   - **When to Use**: To scale your application based on traffic.

2. **Load Balancing**:
   - **Definition**: Distributes traffic across multiple EC2 instances.
   - **When to Use**: To ensure high availability and efficient traffic distribution.

3. **Security Group**:
   - **Definition**: A virtual firewall that controls inbound and outbound traffic for EC2 instances.
   - **When to Use**: To restrict access to EC2 instances based on IP, protocol, and port.

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

---

## Lesson 4: Database Services

### Aurora and RDS:
- **Definition**: Managed relational databases, with Aurora providing higher performance for MySQL and PostgreSQL.
- **When to Use**: For scalable, managed relational databases with high availability.

### DynamoDB:
- **Definition**: Managed NoSQL database for high-throughput, low-latency.
- **When to Use**: For scalable NoSQL applications with low-latency requirements.

---

## Lesson 5: Networking and Content Delivery

### VPC - Virtual Private Cloud:
- **Definition**: A private cloud network where you control your resources.
- **When to Use**: For secure, isolated cloud environments.

1. **Subnets**:
   - **Definition**: Segments of a VPC’s IP range.
   - **When to Use**: To organize and secure resources.

2. **Route Tables**:
   - **Definition**: Directs traffic in and out of subnets.
   - **When to Use**: To manage data flow.

3. **Internet Gateways**:
   - **Definition**: Connects a VPC to the internet.
   - **When to Use**: When VPC resources need internet access.

### DNS (Domain Name System):
- **Definition**: A system that translates domain names (e.g., example.com) into IP addresses that computers use to identify each other.
- **When to Use**: To make websites accessible with human-readable names instead of complex numerical IP addresses.

### Amazon Route 53:
- **Definition**: AWS’s scalable and highly available DNS service that routes user requests to applications running on AWS or other infrastructures.
- **When to Use**: To manage domain registration, DNS routing, and health checking for web applications.
