# 🌐 AWS S3 Static Website Hosting with Security & Disaster Recovery
Secure Static Website Hosting on AWS with IAM, Versioning, Lifecycle Rules $ CRR
This project showcases how to build and deploy a *secure, **cost-optimized, and **fault-tolerant static website* using core AWS services. It was built as part of my learning experience with *ALX Africa Cloud Computing* and reflects key principles of cloud architecture and security.

---

## 📌 Project Overview

This project simulates a real-world e-commerce or marketing website scenario. It focuses on:
- Hosting a static website using *Amazon S3*
- Managing secure access through *IAM*
- Implementing *versioning* for data protection
- Configuring *lifecycle rules* to reduce storage cost
- Enabling *cross-region replication (CRR)* for disaster recovery

---

## 🧠 Key Concepts Demonstrated

- ✅ Static Website Hosting on Amazon S3
- 🔐 Fine-grained access control using IAM users, groups, and custom policies
- ♻ Versioning for object recovery
- 💰 Lifecycle management to transition data to S3 Infrequent Access and automate cleanup
- 🌍 Cross-Region Replication for fault tolerance and regional backup
- 📊 Logging & Monitoring with CloudTrail and CloudWatch

---

## 🧰 Tools & Services Used

- *Amazon S3* – static site hosting, image storage  
- *IAM* – user roles, least privilege policies  
- *Amazon RDS (optional)* – structured relational data  
- *Amazon CloudFront* – fast content delivery  
- *AWS WAF* – protection against web exploits  
- *Amazon EC2 (optional)* – backend hosting  
- *CloudWatch & CloudTrail* – monitoring and auditing  
- *Figma* – architectural diagram  
- *Git + GitHub* – version control and publishing

---

## 🗂 Folder Structure

aws-s3-static-site-project/
├── index.html
├── error.html
├── css/
│   └── style.css
├── images/
│   └── logo.png
├── architecture-diagram.png
├── README.md

---

## 🧪 Testing & Verification

### 🔹 IAM Test:
- User Victor (with limited permissions) attempted to create a bucket → *Access Denied* ✅

### 🔹 Versioning:
- Uploaded multiple versions of index.html and restored older versions via S3 UI

### 🔹 Lifecycle Rule:
- Transition to S3 IA after 30 days  
- Delete previous versions after 365 days

### 🔹 CRR:
- Confirmed files replicated from us-east-1 to us-west-2 bucket within seconds

---

## 🖼 Architecture Diagram

![AWS Static Website Architecture](architecture-diagram.png)

> This visual outlines the flow from the user through CloudFront and WAF to S3, IAM, EC2 (optional), and supporting services.

---

## 🌐 Live Demo

🔗 [Live S3 Website](http://stnicholas-startup-static-website.s3-website-us-east-1.amazonaws.com)

---

## 🙏 Acknowledgments

Special thanks to my *technical mentor* for the insightful guidance, and to *ALX Africa* for providing the opportunity to learn and apply AWS solutions in a hands-on environment.

---

## 📫 Connect with Me

*Ojinni Oluwafemi Nicholas*  
📍 Lagos, Nigeria  
🔗 [LinkedIn](https://www.linkedin.com/in/ojinni-oluwafemi11/)  
✉ ojinnin@gmail.com

---

## 🏷 Tags

#AWS #S3 #IAM #CloudComputing #DevOps #ALXAfrica #DisasterRecovery #Versioning #LifecyclePolicy #StaticWebsite #SolutionArchitect #CloudProjects
