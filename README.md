# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

# Name: Naveen Jaisanker
# Register Number: 212224110039

# Aim
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.  

# Procedure

## a) Steps to Create a First S3 Bucket

1. *Sign in to the AWS Management Console*  
   Go to [AWS S3 Console](https://console.aws.amazon.com/s3).

2. *Open the S3 Service*  
   In the console, type *S3* in the search bar and select *S3* to open the service dashboard.

3. *Create Bucket*  
   Click the *Create bucket* button.

4. *Configure Bucket Settings*  
   - *Bucket name:* Choose a globally unique name.  
   - *AWS Region:* Select the region where you want to store your data.

5. *Object Ownership*  
   Choose between:  
   - *ACLs disabled (recommended):* Bucket owner has full control.  
   - *ACLs enabled:* Control access via access control lists.

6. *Block Public Access Settings*  
   By default, all public access is blocked. Leave it as-is unless you need public access.

7. *Bucket Versioning (optional)*  
   Choose whether to enable versioning for objects in the bucket.

8. *Encryption (optional)*  
   Select encryption options: *SSE-S3, **SSE-KMS, or **none*.

9. *Advanced Settings (optional)*  
   Add tags, configure logging, etc.

10. *Create the Bucket*  
    Click *Create bucket* at the bottom of the page.

---

## b) Steps to Launch an EC2 Instance

1. Go to the *EC2 Dashboard* in AWS Console.  
2. Click on *Launch Instance*.  
3. Choose an *Amazon Machine Image (AMI)* (e.g., Amazon Linux).  
4. Select an *instance type* (e.g., t2.micro for Free Tier).  
5. Create or choose a *key pair* for SSH access.  
6. Configure *network settings* (use default VPC/subnet).  
7. Configure *storage* (default root volume is fine).  
8. Review the settings and click *Launch Instance*.  
9. Wait for the instance to enter the *running state*.

---

## c) Connect to Your Instance

- *Linux:* Use SSH command with your .pem key.  
- *Windows:* Use RDP with decrypted admin password.

---

## d) Steps to Clean Up (Terminate the Instance)

1. Go to *EC2 Instances*.  
2. Select your instance → *Instance State* → *Terminate*.

---

# Output

<img width="1917" height="990" alt="image" src="https://github.com/user-attachments/assets/f665eb9f-1dcd-4db4-aed1-9463e537afa2" />
<img width="1916" height="992" alt="image" src="https://github.com/user-attachments/assets/35c648f1-4b22-4959-a394-ac360079cc99" />

<img width="1917" height="988" alt="image" src="https://github.com/user-attachments/assets/1117e733-92ed-4b7e-930a-20b452eb6df3" />
<img width="1917" height="988" alt="image" src="https://github.com/user-attachments/assets/0085e6d4-5589-450e-b65d-5862edd9178f" />

<img width="1917" height="992" alt="image" src="https://github.com/user-attachments/assets/b5bcf79b-a323-4636-b73c-12032bc4c1e6" />
<img width="1917" height="972" alt="image" src="https://github.com/user-attachments/assets/90217836-2a1c-4b41-a199-270a29abec61" />

<img width="1917" height="992" alt="image" src="https://github.com/user-attachments/assets/69e81d11-7f21-47ab-a4d4-b29ee09741f3" />

<img width="1917" height="997" alt="image" src="https://github.com/user-attachments/assets/cf967233-723d-47c4-848f-0e394787e30b" />
<img width="1917" height="985" alt="image" src="https://github.com/user-attachments/assets/2cc5ac4c-d2bb-4e2b-acdf-c2e75bc9551d" />
<img width="1917" height="985" alt="image" src="https://github.com/user-attachments/assets/cc154599-3a54-49ef-b9ca-c8e1770a92e6" />
<img width="1917" height="991" alt="image" src="https://github.com/user-attachments/assets/ff50feb3-b194-4f3c-b18c-e6004735b933" />
<img width="1917" height="992" alt="image" src="https://github.com/user-attachments/assets/8aca6c88-d34e-484b-b214-06b935d1792e" />
<img width="1267" height="195" alt="image" src="https://github.com/user-attachments/assets/501cf803-4774-4d2b-9787-d946ca1942d2" />


---

# Result
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) instance has been successfully created and launched in AWS.
