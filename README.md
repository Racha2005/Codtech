# ☁️ CODTECH IT Solutions – Cloud Computing Internship

## 📘 Project Overview

This internship provided hands-on experience in **Cloud Computing** using **Amazon Web Services (AWS)**.  
The focus was to design, deploy, and secure scalable cloud infrastructure while gaining real-world exposure to resource management, automation, and monitoring.

The internship was divided into four key modules — covering **storage, compute, networking, and security management**, each aimed at simulating enterprise-level cloud operations.



## 🎯 Objectives

- Understand and apply **core AWS services** such as S3, EC2, VPC/ELB, and IAM.  
- Learn how to **deploy and manage scalable cloud infrastructure**.  
- Implement **security controls, monitoring, and automation** using AWS tools.  
- Gain experience with **multi-cloud integration** and real-time alerting.  
- Strengthen problem-solving and configuration skills for cloud-based projects.



## ⚙️ Tools & Technologies Used

| Category | Tools / Services |
|-----------|------------------|
| Cloud Platform | AWS (S3, EC2, VPC, ELB, IAM, CloudWatch, SNS) |
| Development | Visual Studio Code |
| Automation | AWS CLI |
| Version Control | Git, GitHub |
| Security | Google Authenticator (MFA) |
| OS Used | Amazon Linux 2023 |



## 🧩 Tasks Overview

### **Task 1 – Secure Cloud Storage (Amazon S3)**
- Configured S3 buckets for object storage  
- Enabled versioning & encryption for data safety  
- Managed IAM permissions for secure access  
- **Outcome:** Secure and reliable data storage with backup capability  



### **Task 2 – Compute Deployment & Monitoring**
- Launched EC2 instances with Linux OS  
- Installed Apache server & hosted static website  
- Configured CloudWatch for CPU monitoring  
- **Outcome:** Functional web hosting with real-time performance alerts  



### **Task 3 – Multi-Cloud Integration (AWS + GCP)**
- Connected EC2 with GCP Compute Engine  
- Hosted web pages in both cloud platforms  
- Tested redundancy and failover communication  
- **Outcome:** Cross-platform availability & improved resilience  



### **Task 4 – Cloud Security & Alert Automation**
- Configured IAM users, roles & least-privilege access  
- Enabled Multi-Factor Authentication (MFA)  
- Created CloudWatch alerts linked to SNS notifications  
- **Outcome:** Strong cloud security with automated alerts  



## 🚀 How to Run the Project

### Launch EC2 + Apache
```bash
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
