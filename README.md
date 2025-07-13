# week5-AribaShafaqat

This project demonstrates how to deploy a cloud-based web application using Huawei Cloud services including ECS, RDS, VPC, ELB, Auto Scaling, and LAMP environment setup. The goal is to ensure high availability and scalability.

📄 [Download Assignment Report](./Ariba%20Shafaqat%20assignment%201.docx)

---

## ✅ Tasks Completed

### 1. Creating Network Resources
- **Created a VPC** in the AP-Singapore region.
- **Configured a Security Group** with inbound rules allowing all traffic.
  
### 2. Deploying Compute and Database
- **Purchased ECS (Elastic Cloud Server)** with CentOS 7.6.
- **Set up a custom security group, VPC, and EIP** during ECS creation.
- **Purchased an RDS instance** using MySQL 8.0 with high availability.

### 3. LAMP Stack Installation
- Installed **Linux, Apache, MySQL, and PHP** on ECS to host a basic website.

### 4. Load Balancer and Auto Scaling
- **Created a shared Elastic Load Balancer (ELB)** and configured listeners.
- **Created an ECS image** and used it to configure Auto Scaling (AS).
- **Defined AS Policies** to automatically scale in/out based on CPU usage.

### 5. Access and Monitoring
- **Verified website access** through ELB’s public IP.
- **Monitored resources** and confirmed automatic ECS scaling behavior.

---

## 🌐 Technologies Used
- Huawei Cloud: ECS, RDS, VPC, ELB, IMS, AS
- OS: CentOS 7.6
- Tools: Apache, MySQL, PHP

---

## 📸 Screenshots and Report
All steps with screenshots and details are included in the downloadable assignment report linked above.
