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


## 📸 Screenshots

Screenshots will be added here during the implementation.

---

## 🛠️ Implementation Steps

### Step 1: Create the Requester VPC

The first Virtual Private Cloud (VPC) was created as the **Requester VPC** with the required IPv4 CIDR block. This VPC initiates the VPC Peering request and serves as one side of the private network.

![Requester VPC](Screenshot/01-requester-vpc.png)

---

## ✅ Result

Successfully established communication between EC2 instances deployed in different VPCs using AWS VPC Peering.