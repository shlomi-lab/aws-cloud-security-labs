# AWS Cloud Security Labs

Hands-on AWS Cloud Security labs focused on CloudTrail investigation, IAM security, cross-account access, AWS CLI administration, and cloud incident response.

---

# Overview

This repository documents a series of practical AWS Security labs completed on the **Flaws2.Cloud** platform.

The project demonstrates how to securely access multiple AWS accounts, collect CloudTrail logs, analyze JSON audit data using **jq**, investigate suspicious API activity, and identify potential credential compromise scenarios.

The exercises simulate real-world cloud security investigations commonly performed by Cloud Security Engineers, SOC Analysts, and Incident Responders.

---

# Objectives

- Configure and authenticate the AWS CLI
- Verify AWS identities using AWS STS
- Download CloudTrail logs from Amazon S3
- Configure secure cross-account access using IAM Roles
- Assume IAM roles through AWS CLI profiles
- Analyze CloudTrail JSON logs with jq
- Build event timelines
- Investigate suspicious AWS API activity
- Detect potential credential compromise
- Export investigation reports for further analysis

---

# Technologies

- AWS CLI
- AWS IAM
- AWS STS
- Amazon S3
- AWS CloudTrail
- IAM Roles
- Cross-Account Role Assumption
- jq
- JSON
- Kali Linux
- Bash

---

# Skills Demonstrated

### AWS Identity & Access Management

- IAM Users
- IAM Roles
- Role Assumption
- Temporary Credentials
- Cross-Account Authentication

### AWS Logging & Monitoring

- CloudTrail
- Amazon S3
- Audit Log Collection
- API Activity Analysis

### Cloud Investigation

- Timeline Reconstruction
- Event Correlation
- Identity Tracking
- Source IP Analysis
- Suspicious API Investigation

### Linux & Automation

- AWS CLI
- Bash
- jq
- JSON Parsing
- Report Generation

---

# Repository Contents

| File | Description |
|------|-------------|
| AWS-Cloud-Security-Labs.pdf | Complete project documentation |
| images/ | Screenshots demonstrating each investigation step |
| README.md | Project overview |

---

# Security Workflow

```
AWS CLI Authentication
        │
        ▼
AWS STS Identity Verification
        │
        ▼
Cross-Account IAM Role Assumption
        │
        ▼
Amazon S3 CloudTrail Download
        │
        ▼
CloudTrail JSON Processing
        │
        ▼
jq Log Analysis
        │
        ▼
Timeline Reconstruction
        │
        ▼
Credential Compromise Investigation
```

---

# Learning Outcomes

This project demonstrates practical experience with:

- AWS account administration
- Secure authentication using IAM Roles
- Cross-account access management
- CloudTrail forensic investigations
- Cloud log analysis
- JSON processing with jq
- Security event correlation
- Cloud incident response methodology

---

# Platform

Lab Environment:

**Flaws2.Cloud**

AWS Services:

- AWS Identity and Access Management (IAM)
- AWS Security Token Service (STS)
- Amazon S3
- AWS CloudTrail

Operating System:

- Kali Linux

---

# Disclaimer

This repository contains educational cloud security exercises performed within an intentionally vulnerable laboratory environment.

All activities were conducted in authorized lab environments for learning and research purposes only.
