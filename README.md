# 🛠️ AWS VPC Architecture with Public and Private Subnets

![AWS](https://img.shields.io/badge/AWS-VPC-orange?logo=amazon-aws)
![Region](https://img.shields.io/badge/Region-Asia%20Pacific%20(Mumbai)-blue?logo=aws)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview

This project creates the following architecture in the **AWS (Mumbai)** region:

- 1 Custom VPC
- 2 Public Subnets
- 2 Private Subnets
- 1 Internet Gateway (IGW)
- 1 NAT Gateway
- 2 Route Tables

---

## 🧭 Architecture Diagram
                   
![ChatGPT Image May 18, 2025, 04_38_59 PM](https://github.com/user-attachments/assets/1c16dc34-cdc6-43b8-bfa0-6c7685fb4cae)



---

## ✅ CIDR Planning

| Subnet Name        | CIDR            | AZ            | Type     |
|--------------------|------------------|---------------|----------|
| public-subnet-1    | 172.20.1.0/24     | ap-south-1a   | Public   |
| public-subnet-2    | 172.20.2.0/24     | ap-south-1b   | Public   |
| private-subnet-1   | 172.20.10.0/24    | ap-south-1a   | Private  |
| private-subnet-2   | 172.20.11.0/24    | ap-south-1b   | Private  |

---

## 🧰 Tools Used

- AWS Console
- VPC Wizard
- NAT Gateway, IGW
- Route Tables
- Subnetting

---

## 📜 License

This project is open-sourced under the [MIT License](LICENSE).

---

> Created with ❤️ for AWS networking tutorials.
