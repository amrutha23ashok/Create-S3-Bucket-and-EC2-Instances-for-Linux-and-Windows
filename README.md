 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
## AIM
To Create S3 bucket and EC2 Instances for Linux and Windows.
## PROBLEM STATEMENT
1. This experiment demonstrates the process of setting up cloud infrastructure on AWS by creating an S3 bucket for storage and EC2 instances to host Linux and Windows environments.
2. The goal is to provide an overview of how to configure and interact with these resources effectively, along with commands and screenshots to document the process.

## ALGORITHM
### Step 1:
Log in to AWS Console

### Step 2:
Create an S3 Bucket
Navigate to the S3 service.
Click on Create bucket.
Enter a Bucket name and select a Region.
Configure Bucket settings as required (e.g., versioning, public access).
Click on Create bucket to finalize.

### Step 3: 
Create an EC2 Instance (Linux)
Go to the EC2 service.
Click on Launch Instance.
Select an Amazon Machine Image (AMI) for Linux (e.g., Amazon Linux 2).
Choose an Instance Type (e.g., t2.micro for free tier).
Configure Instance Details, Storage, and Security Group.
Review and click Launch with a key pair (or create one if needed).

### Step 4:
Create an EC2 Instance (Windows)
Return to the EC2 service and click Launch Instance.
Select a Windows AMI (e.g., Windows Server 2019).
Choose the Instance Type.
Configure Instance Details, Storage, and Security Group.
Review and launch with a key pair (for future login).

### Step 5: 
Verify and Connect to Instances
Verify the status of both instances in the EC2 dashboard.
Connect to the Linux instance using SSH.
Connect to the Windows instance using RDP.
## OUTPUT
### REG NUMBER:21222110004
### NAME:AMRUTHA
 ### S3 BUCKET CREATION:
 ![image](https://github.com/user-attachments/assets/fe08ab4a-2600-412f-9017-9de1cf30a5a7)
### CONTENT IN BUCKET :
![image](https://github.com/user-attachments/assets/46ec2dbf-c5e1-484e-a4c4-f8febfbcdc5d)
![image](https://github.com/user-attachments/assets/09013a0c-f162-488d-a163-d0f7954a3046)

### VERSIONING:
![image](https://github.com/user-attachments/assets/ec7d7d80-387b-4f5f-88b7-52bb4ec3fbfd)
### EC2:
![image](https://github.com/user-attachments/assets/7dc06301-0700-4b81-9bbc-3163e55ab152)
### Linux and Windows:
![image](https://github.com/user-attachments/assets/bdab53ad-40cf-4a5f-8030-6c085e23dad3)

![image](https://github.com/user-attachments/assets/b4db27c8-c0b9-470e-be03-39346908cc33)

## RESULT
Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating cloud resource management on AWS.
 

  


