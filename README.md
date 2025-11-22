# AWS Cloud Security Dashboard

## Project Overview
Real-time AWS Cloud Threat Detection & Alerting System using GuardDuty and Security Hub.  
Monitors IAM, S3, and EC2 for unauthorized access, anomalous API calls, and account-level threats.

This project demonstrates the ability to implement a centralized cloud security monitoring system that improves visibility and reduces risk across AWS resources.

---

## Features
- Centralized dashboard for monitoring IAM, S3, and EC2 security events
- Real-time alerts for unauthorized access and anomalous API calls
- Enforced IAM least-privilege policies and MFA validation
- Security Hub integration to consolidate findings from multiple AWS services

---

## Screenshots
![Dashboard](screenshots/dashboard1.png)  
![GuardDuty Findings](screenshots/guardduty-finding.png)  

*Replace these images with your actual screenshots.*

---

## Technologies Used
- **AWS GuardDuty** – Threat detection for AWS resources  
- **AWS Security Hub** – Centralized security findings  
- **AWS CloudTrail** – Logging all API calls and events  
- **IAM, S3, EC2** – Core AWS resources monitored  

---

## How It Works
1. **CloudTrail** logs all account activity across IAM, S3, and EC2.  
2. **GuardDuty** detects anomalies, unauthorized access, and suspicious activity.  
3. **Security Hub** aggregates findings into a unified dashboard.  
4. Alerts are generated in real-time to help respond quickly to potential threats.  

---

## Key Security Practices
- Implemented **IAM least-privilege policies** to limit access.  
- Enforced **MFA** on sensitive accounts.  
- Used **IAM Access Analyzer** to detect risky permissions.  

---

## Outcome / Impact
- Enhanced security visibility across cloud environment.  
- Enabled rapid detection of unauthorized or risky activity.  
- Demonstrated hands-on knowledge of AWS cloud security services and best practices.

