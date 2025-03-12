# aws-journey

Udemy course: https://www.udemy.com/course/introduction-to-cloud-computing-on-amazon-aws-for-beginners/

### Lesson 1: AWS IAM

User: An individual with AWS access.
User Group: A collection of users with the same permissions.
Role: Temporary permissions that can be assumed when needed.


**User Groups & Permissions**
1. Created Admins group with AdministratorAccess.
2. Added Max to Admins to give him admin rights.
3. Created Joe without adding him to Admins, so he had limited access.

**Roles & AssumeRole Setup**
1. Logged in as Max and created ec2-role with EC2 access.
2. Gave Joe permission to assume ec2-role temporarily.
3. Copied the ec2-role URL.
4. Logged in as Joe, pasted the URL, and assumed the role, gaining EC2 access.
