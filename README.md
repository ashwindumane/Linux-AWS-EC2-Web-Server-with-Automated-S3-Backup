# 🚀 Linux & AWS EC2 Web Server with Automated S3 Backup

This project focuses on hands-on practice with Linux and AWS services. A Linux-based web server is deployed on an Amazon EC2 instance to host a simple web application. The application data is automatically backed up to Amazon S3 using shell scripting and cron jobs. This project demonstrates practical skills in Linux server management, AWS EC2, S3 storage, IAM roles, and basic automation.

## 🛠️ Technologies / Services Used

- **Operating System:** Amazon Linux 2023  
- **Cloud Platform:** Amazon Web Services (AWS)  
- **Compute Service:** Amazon EC2  
- **Storage Service:** Amazon S3  
- **Identity & Access Management:** AWS IAM (IAM Role for EC2)  
- **Web Server:** Apache HTTP Server  
- **Automation & Scripting:** Bash (Shell Scripting)  
- **Command Line Tool:** AWS CLI  
- **Scheduling:** Cron  

## Step-by-Step Implementation

### 🔹 Step 1: AWS EC2 Instance Created

<img width="994" height="380" alt="AWS EC2 Instance Created" src="https://github.com/user-attachments/assets/2e2a126d-3d36-4099-8c92-c1fe5e6950f3" />

### 🔹 Step 2: EC2 User Data Configuration

<img width="1046" height="539" alt="EC2 User Data Configuration" src="https://github.com/user-attachments/assets/9ee6ab10-3771-4972-8aef-e7ab44d9d09e" />

### 🔹 Step 3: IAM Role Creation – Trusted Entity Selection

<img width="950" height="432" alt="IAM Trusted Entity Selection" src="https://github.com/user-attachments/assets/9430ff36-ecd3-4e3d-9383-8021a9db97a8" />

### 🔹 Step 4: Attach S3 Permissions to IAM Role

<img width="1017" height="454" alt="Attach S3 Permissions to IAM Role" src="https://github.com/user-attachments/assets/74df85cf-acc2-46f2-ae87-1b974ea01d55" />

### 🔹 Step 5: Name, Review, and Create IAM Role

<img width="1021" height="457" alt="Create IAM Role" src="https://github.com/user-attachments/assets/87a184c9-ad56-41bd-a5f7-cddf88e0a9b9" />

### 🔹 Step 6: Review Permissions and Finalize IAM Role

<img width="975" height="439" alt="Review IAM Role Permissions" src="https://github.com/user-attachments/assets/8259bf3d-27c4-4a2d-87da-4c3e8b8cdf7e" />

### 🔹 Step 7: IAM Role Successfully Created and Verified

<img width="975" height="417" alt="IAM Role Successfully Created" src="https://github.com/user-attachments/assets/a4287bde-88c7-4fb0-b596-94f52b084341" />

### 🔹 Step 8: Attach IAM Role to EC2 Instance

<img width="975" height="385" alt="Attach IAM Role to EC2" src="https://github.com/user-attachments/assets/dfa27f88-0cdd-4c77-8822-1352c9f481f1" />

### 🔹 Step 9: Amazon S3 Bucket Creation

<img width="975" height="510" alt="Amazon S3 Bucket Creation" src="https://github.com/user-attachments/assets/0d3f0e2d-0ac5-4114-9863-83dbe63b7486" />

### 🔹 Step 10: S3 Backup Shell Script Configuration

<img width="975" height="377" alt="S3 Backup Script Configuration" src="https://github.com/user-attachments/assets/1b24166e-4e66-46dd-bf27-a61b44b59045" />

### 🔹 Step 11: Backup Script Finalization and Save

<img width="764" height="496" alt="Backup Script Finalized" src="https://github.com/user-attachments/assets/c6a10fb5-921c-42b8-839b-a62992ed6f2f" />

### 🔹 Step 12: Backup Script Execution and Upload to S3

<img width="975" height="118" alt="Backup Script Execution" src="https://github.com/user-attachments/assets/df8d9880-73aa-422d-bd35-25e66ab19961" />

### 🔹 Step 13: Verification of Backup File in Amazon S3

<img width="1043" height="464" alt="Backup File in S3" src="https://github.com/user-attachments/assets/cb0b1714-1772-488a-9dd9-36ff7ba44290" />

### 🔹 Step 14: Backup Object Details in Amazon S3

<img width="1042" height="468" alt="S3 Backup Object Details" src="https://github.com/user-attachments/assets/e476ce9e-f113-4029-a63a-43ac64eb009b" />

### 🔹 Step 15: Web Application Successfully Deployed on EC2

<img width="1072" height="592" alt="Web Application Running on EC2" src="https://github.com/user-attachments/assets/8c65b13d-9103-44e4-ad3a-6e2f535719de" />

## ✅ Project Outcome

- Linux web server deployed on AWS EC2  
- Automated backup solution implemented using shell scripting and cron  
- Secure AWS access configured using IAM roles  
- Backup data successfully stored and verified in Amazon S3

## 🎯 Conclusion

This project provides hands-on experience with Linux administration, AWS cloud services, and automation. It demonstrates how to deploy a web server on AWS EC2 and implement a secure, automated backup solution using Amazon S3.
