# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
# NAME: Sanjeev Kumar S
# REG NO: 2122224040290

## Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

## Procedure: 

## a) Steps to Create Your First S3 Bucket

### Step 1: Sign in to the AWS Management Console
- Visit: https://console.aws.amazon.com/s3

### Step 2: Open the S3 Service
- In the console, type **S3** in the search bar and select **S3** to open the dashboard.

### Step 3: Create Bucket
- Click the **Create bucket** button.

### Step 4: Configure Bucket Settings
- **Bucket name:** Choose a globally unique name.
- **AWS Region:** Select the region to store your data.

### Step 5: Object Ownership
- Choose one:
  - **ACLs disabled** (recommended) – Bucket owner has full control.
  - **ACLs enabled** – Control access using access control lists.

### Step 6: Block Public Access Settings
- By default, all public access is blocked.
- Leave as-is unless you require public access.

### Step 7: Bucket Versioning (optional)
- Choose whether to enable versioning for objects in the bucket.

### Step 8: Encryption (optional)
- Select encryption: **SSE-S3**, **SSE-KMS**, or **None**.

### Step 9: Advanced Settings (optional)
- Add tags, configure logging, and other settings as needed.

### Step 10: Create the Bucket
- Click **Create bucket** at the bottom of the page.

---

## b) i. Steps to Launch an EC2 Instance

1. Go to the **EC2 Dashboard** in AWS Console.
2. Click **Launch Instance**.
3. Choose an **Amazon Machine Image (AMI)** (e.g., Amazon Linux).
4. Select an **instance type** (e.g., t2.micro for Free Tier).
5. Create or choose a **key pair** for SSH access.
6. Configure **network settings** (use default VPC/subnet).
7. Configure **storage** (default root volume is fine).
8. Review the settings and click **Launch Instance**.
9. Wait for the instance to enter the **running** state.

---

## c) Step 3: Connect to Your Instance

- **Linux:** Use the SSH command with your `.pem` key.
- **Windows:** Use RDP with the decrypted administrator password.

---

## d) Steps to Clean Up (Terminate the Instance)

1. Go to **EC2 Instances**.
2. Select your instance.
3. Click **Instance State** → **Terminate**.

## Output:

### Simple Storage Device:

![444751813-cbf99d29-f8c8-4601-8ce3-2813bf4599d9](https://github.com/user-attachments/assets/02472623-2cc4-4706-bd55-08f264a8ac15)

### EC2(Elastic Cloud Compute) 

![444751820-36c30ac3-212a-4875-8f54-94360cd25c65](https://github.com/user-attachments/assets/39ae9d23-3bb2-419a-9c62-38ec623501af)


## Result:

Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS.
