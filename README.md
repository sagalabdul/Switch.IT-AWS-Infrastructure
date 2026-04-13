# 🔐 Secure Cloud Infrastructure for Switch.IT

> Designed by **Sagal Abdullahi**  
> A secure, scalable AWS cloud architecture for a global career-switching platform.

---

## 📌 Project Overview

Switch.IT is a start-up expanding globally that needed a secure cloud infrastructure
to handle sensitive user data (PII), comply with **EU GDPR**, and scale internationally.
This project designs that infrastructure using AWS best practices.

---

## 🛡️ Core Security Principles

| Principle | Description |
|---|---|
| 🔒 Security by Design | Security controls built in from day one |
| 👤 Least Privilege Access | Minimum permissions for every user & service |
| 🧱 Defense in Depth | Multiple independent layers of protection |
| 📊 Continuous Monitoring | 24/7 threat detection and compliance tracking |

---

## ☁️ AWS Services Used

**Edge & Networking**
`Route 53` `CloudFront` `AWS WAF` `AWS Shield` `API Gateway` `VPC`

**Compute & Processing**
`ECS Fargate` `AWS Lambda` `Auto Scaling` `ALB`

**Storage & Database**
`S3 (KMS Encrypted)` `RDS Multi-AZ (KMS Encrypted)` `ElastiCache (Redis)`

**Security & Identity**
`IAM` `AWS Cognito` `MFA` `KMS` `Secrets Manager`

**Monitoring & Compliance**
`CloudWatch` `CloudTrail` `GuardDuty` `Security Hub`

---

## 🏗️ Architecture Diagram

![Switch.IT AWS Architecture](./Switch.IT-AWS-Infrastructure.png)

---

## 📋 Key Features

- ✅ GDPR compliant — all PII encrypted, access controlled and logged
- ✅ DDoS protection via AWS WAF and Shield at the edge
- ✅ Network isolation — database and storage never exposed to the internet
- ✅ All data encrypted at rest (KMS) and in transit (HTTPS/TLS)
- ✅ Secrets automatically rotated via AWS Secrets Manager
- ✅ Multi-AZ database for high availability and disaster recovery

---

*Built as part of a cloud security project for Switch.IT*
