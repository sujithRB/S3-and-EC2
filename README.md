# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
# Name: SUJITH RB
# register number:212224103003

# AIM :
To create an AWS account, set up a root user, and create an IAM user with specified permissions.

# PROBLEM STATEMENT :
This experiment involves creating an AWS account, configuring security settings for the root user, and setting up an IAM user. IAM users allow for secure, managed access to AWS resources without exposing the main account's root credentials.

# Procedure:
a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3.

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard.

Step 3: Create Bucket Click the Create bucket button.

Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access.

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none).

Step 9: Advanced Settings (optional) Add tags, configure logging, etc.

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

b) i. Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

Wait for the instance to enter the running state.

c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key. • Windows: Use RDP with decrypted admin password.

d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances. Select your instance → Instance State → Terminate

# Output:

 <img width="1919" height="1078" alt="Screenshot 2025-10-10 142104" src="https://github.com/user-attachments/assets/a9c27dfa-b7ac-425f-ac76-68acb8fe51f5" />

<img width="1920" height="1080" alt="Screenshot (276)" src="https://github.com/user-attachments/assets/bab2db9e-671c-4df9-8566-f62d8cfd7524" />

<img width="1920" height="1080" alt="Screenshot (277)" src="https://github.com/user-attachments/assets/2ff55ffb-c2b5-4726-a667-28f23d7844cd" />

# RESULT:
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
