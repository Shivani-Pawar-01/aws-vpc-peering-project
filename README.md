# 🚀 AWS VPC Peering Project

## 📖 Project Overview

This project demonstrates how to establish private communication between two Amazon Virtual Private Clouds (VPCs) using **AWS VPC Peering**.

The implementation includes:

- Creating two VPCs (Requester & Accepter)
- Creating Public Subnets
- Configuring Route Tables
- Attaching Internet Gateways
- Creating a VPC Peering Connection
- Launching EC2 Instances
- Verifying connectivity using private IP addresses

---

## 🛠 AWS Services Used

- Amazon VPC
- Amazon EC2
- Route Tables
- Internet Gateway
- VPC Peering
- Security Groups

---

## 📌 Project Objectives

- Build two isolated VPCs
- Configure networking resources
- Establish secure private communication
- Verify connectivity using ICMP (ping)

---

## 🏗 Architecture

                Internet
                    │
          ┌─────────┴─────────┐
          │                   │
      Internet Gateway    Internet Gateway
          │                   │
    Requester VPC        Accepter VPC
      10.0.0.0/16        192.168.0.0/16
          │                   │
     Public Subnet      Public Subnet
          │                   │
      EC2 Instance  ◄────VPC Peering────► EC2 Instance

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

- Amazon VPC Networking
- CIDR Block Planning
- Public Subnets
- Route Tables
- Internet Gateway (IGW)
- Security Groups
- EC2 Networking
- VPC Peering
- Private IP Communication
- AWS Networking Fundamentals

---

## ✅ Project Outcome

Successfully created two isolated Amazon VPCs and established secure private communication between them using AWS VPC Peering. Configured subnets, route tables, internet gateways, and EC2 instances, then verified connectivity using private IP addresses through ICMP (ping). This project demonstrates a practical understanding of AWS networking concepts and inter-VPC communication.

---

## 👩‍💻 Author

**Shivani Pawar**

**DevOps Engineer | AWS | Docker | Kubernetes | Terraform | Jenkins | Linux**

- GitHub: https://github.com/Shivani-Pawar-01
- LinkedIn: https://www.linkedin.com/in/shivani-pawar01

---

⭐ **If you found this project helpful, consider giving it a Star!**

