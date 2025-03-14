# aws-journey
Udemy course: https://www.udemy.com/course/introduction-to-cloud-computing-on-amazon-aws-for-beginners/

### Lesson 1: IAM

- **User:** An individual with AWS access.
- **User Group:** A collection of users with the same permissions.
- **Role:** Temporary permissions that can be assumed when needed.
- **Policy:** Defines permissions for AWS actions.


### Lesson 2: EC2

- **EC2:** Virtual servers in the cloud.

**Auto Scaling:**
- **Launch Template:** A template for launching EC2 instances.
- **Auto Scaling Group:** Adjusts the number of EC2 instances based on demand using a Launch Template.

**Load Balancing:**
- **Target Group:** A set of EC2 instances (or Auto Scaling Group) that receive traffic from the Load Balancer. It checks instance health before routing traffic.
- **Load Balancer:** Distributes incoming traffic to EC2 instances in the Target Group to ensure smooth performance.
