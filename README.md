# AWS Cloud Security Dashboard

## Project Overview
Real-time AWS Cloud Threat Detection & Alerting System using GuardDuty and Security Hub.  
Monitors IAM and S3 for unauthorized access and account-level threats.

This project demonstrates the ability to implement a basic cloud security monitoring system in AWS.

---

## Features
- Monitors IAM users and S3 buckets for suspicious activity  
- Real-time alerting using GuardDuty findings  
- Security Hub integration to centralize findings  

---

## Screenshots
![GuardDuty Findings](screenshots/guardduty-finding.png)  
![S3 & IAM Dashboard](screenshots/dashboard1.png)  

*Replace these images with your actual screenshots.*

---

## Technologies Used
- **AWS GuardDuty** – Threat detection for AWS resources  
- **AWS Security Hub** – Centralized security findings  
- **CloudTrail** – Logging all account activity  
- **IAM** – User and permission monitoring  
- **S3** – Bucket security monitoring  

---

## How It Works
1. **CloudTrail** logs all account activity across IAM and S3.  
2. **GuardDuty** detects anomalies, unauthorized access, and suspicious activity.  
3. **Security Hub** aggregates findings into a unified dashboard.  
4. Alerts are generated in real-time to help respond quickly to potential threats.

---

## Outcome / Impact
- Improved security visibility for IAM and S3  
- Enabled detection of unauthorized or risky activity  
- Demonstrated practical hands-on knowledge of AWS cloud security services
