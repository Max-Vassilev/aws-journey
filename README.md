# aws-journey
Udemy course: https://www.udemy.com/course/introduction-to-cloud-computing-on-amazon-aws-for-beginners/

### Lesson 1: AWS IAM

- **User:** An individual with AWS access.
- **User Group:** A collection of users with the same permissions.
- **Role:** Temporary permissions that can be assumed when needed.

**Example:**
- A user group: "Developers" (all devs get the same permissions).
- A role: "S3ReadAccess" (any user or service can temporarily assume this role to read S3).


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
