# EduCloud – Secure Cloud File Sharing System

# Author

Anil Vishwakarma N

LinkedIn: https:https://www.linkedin.com/in/anil-vishwakarma14?utm_source=share_via&utm_content=profile&utm_medium=member_android

---

# Project Overview

EduCloud is a cloud-based file sharing system designed for trainers and students.
It provides secure access to study materials, assignment submission, and automated backup using AWS and Linux.

---

# Key Features

* Role-based access (Trainer / Student / Support)
* Secure file upload and download
* Assignment submission system
* Automated backup using cron jobs
* Cloud storage integration (AWS S3)
* Notification system using Lambda & SNS
* Scalable architecture using Auto Scaling

---

# Technologies Used

* AWS (EC2, S3, RDS, Lambda, SNS, CloudFront, Auto Scaling)
* Linux (User Management, Permissions, ACL)
* Apache Web Server
* Shell Scripting
* MySQL (RDS)

---

# What I Implemented

# AWS Infrastructure

* Created custom VPC with public & private subnets 
* Configured Internet Gateway & NAT Gateway 
* Deployed Bastion Host and Private EC2 instances 
* Set up Application Load Balancer & Auto Scaling Group 
* Integrated S3 buckets for storage and backup 
* Configured RDS MySQL database 
* Implemented Lambda + SNS for notifications 
* Used CloudFront for content delivery 

---

# Linux Implementation

* Created users and groups (trainers, students, support) 
* Implemented file permissions and ACL for access control 
* Configured Apache web server for portal hosting 
* Automated backups using cron jobs 
* Implemented LVM and disk encryption (LUKS) 
* Configured NFS and FTP services 

---

# Workflow

1. User accesses system via Load Balancer
2. Request goes to private EC2 instance
3. Trainer uploads materials → stored in S3
4. S3 triggers Lambda → sends notification via SNS
5. Students download materials
6. Assignments stored and recorded in RDS
7. Backup automated via cron jobs

---

# Project Structure

* project diagrams → architecture diagrams
* project setup → Linux commands and configuration
* PDFs → detailed report and screenshots


---

# Documentation

* EduCloud_Project_Report.pdf
* EduCloud_Full_Screenshots.pdf

---

# Future Scope

* Mobile application integration
* Live chat / discussion forum
* Improved UI

---

# Conclusion

This project demonstrates real-world implementation of AWS cloud services and Linux system administration to build a secure, scalable file sharing platform.
