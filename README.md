# aws-journey
Udemy course: https://www.udemy.com/course/introduction-to-cloud-computing-on-amazon-aws-for-beginners/

### Lesson 1: AWS IAM

- **User:** An individual with AWS access.
- **User Group:** A collection of users with the same permissions.
- **Role:** Temporary permissions that can be assumed when needed.

**Example:**
- A user group: "Developers" (all devs get the same permissions).
- A role: "S3ReadAccess" (any user or service can temporarily assume this role to read S3).

**IAM User Groups:**
1. I created "Admins" group with AdministratorAccess policy.
2. Then I created user "Max" and added him to Admins to give him admin rights.

**IAM Roles:**
1. I created new user "Joe" without adding him to any group, so he had limited access.
2. Logged in as "Max" and created ec2-role with EC2 access.
3. Gave "Joe" permission to assume ec2-role temporarily.
4. Copied the ec2-role URL.
5. Logged in as "Joe", pasted the URL, and assumed the role, gaining EC2 access.

### Lesson 2: EC2

**Steps Followed:**
- Created a new IAM role `S3ReadOnly` with S3 read-only access for EC2.
- Went back to EC2, selected the Linux instance.
- Went to **Actions > Security > Modify IAM Role**.
- Assigned the `S3ReadOnly` role to the instance.

**Problem Faced:**
- The instance had no permissions to access S3.

**Fix:**
- Created and attached the `S3ReadOnly` IAM role to grant S3 read-only access.
