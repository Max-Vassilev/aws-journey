# aws-journey
Udemy course: https://www.udemy.com/course/introduction-to-cloud-computing-on-amazon-aws-for-beginners/

### Lesson 1: AWS IAM

- User: An individual with AWS access.
- User Group: A collection of users with the same permissions.
- Role: Temporary permissions that can be assumed when needed.

**IAM User Groups**

1. I created Admins group with AdministratorAccess policy.
2. Than I Added Max to Admins to give him admin rights.

**IAM Roles**

1. I created new user Joe without adding him to any group, so he had limited access.
2. Logged in as Max and created ec2-role with EC2 access.
3. Gave Joe permission to assume ec2-role temporarily.
4. Copied the ec2-role URL.
5. Logged in as Joe, pasted the URL, and assumed the role, gaining EC2 access.
