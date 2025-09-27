# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
# NAME: KARTHICK K
# REG NO: 212222040070
# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3.

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard.

Step 3: Create Bucket Click the Create bucket button.

Step 4: Configure Bucket Settings

# • Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access.

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none).

Step 9: Advanced Settings (optional) Add tags, configure logging, etc.

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

b) i. Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

# Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

# Wait for the instance to enter the running state.

c) Step 3: Connect to Your Instance

# • Linux: Use SSH command with your .pem key. • Windows: Use RDP with decrypted admin password.

d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances. Select your instance → Instance State → Terminate.

# OUTPUT:
# CREATING A NEW INSTANCES:
<img width="1279" height="561" alt="Screenshot 2025-09-27 105027" src="https://github.com/user-attachments/assets/31e400a8-3f25-44d5-8a1e-2d5ffbeed3ae" />

# CREATING A BUCKET IN S3:

<img width="1262" height="552" alt="Screenshot 2025-09-27 105222" src="https://github.com/user-attachments/assets/4fa83fbb-9813-44e1-8503-b5b2609463fa" />

# CREATING NEW INSTANCES IN EC2:

<img width="1266" height="555" alt="Screenshot 2025-09-27 111355" src="https://github.com/user-attachments/assets/62264ccf-28a3-4be0-9b8d-e4368a9c397c" />

# OVERVIEW OF EC2 STORAGE INSTANCES:

<img width="1265" height="556" alt="Screenshot 2025-09-27 111642" src="https://github.com/user-attachments/assets/e2cb1ece-7b7f-4647-934a-9324c45b8093" />


# INSIDE NEW INSTANCES STORAGE EC2:
<img width="1265" height="560" alt="Screenshot 2025-09-27 111832" src="https://github.com/user-attachments/assets/61ba489c-42e5-4463-9447-a9b72ab8d617" />

# RESULT
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
