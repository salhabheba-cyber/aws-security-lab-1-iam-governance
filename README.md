# 🔐 Lab 1: Complete IAM Governance & Access Control System

## 📋 Overview

This lab demonstrates a production-ready IAM security implementation on AWS following industry best practices.

### What I Built

| Component | Implementation |
|-----------|----------------|
| Password Policy | 14 chars, 90-day expiry, 24-pass history, complexity requirements |
| IAM Groups | SecurityAuditors, Developers, DevOpsEngineers |
| Custom Policies | DevS3LimitedAccess, RequireMFA |
| Users Created | alice.security, bob.developer, carol.devops |
| Audit Logging | CloudTrail enabled across all regions |
| Monitoring | CloudWatch Dashboard + CloudWatch Alarms |
| Alerting | SNS email notifications |

## 🏗️ Architecture Diagram


## 📸 Screenshots

| # | Description |
|---|-------------|
| 1 | Password policy enabled (14 chars, 90 days, 24 history) |
| 2 | IAM Groups with attached policies |
| 3 | Custom policy: DevS3LimitedAccess (read-only S3, deny delete) |
| 4 | Users list with assigned groups |
| 5 | RequireMFA policy attached to all users |
| 6 | MFA setup with Authenticator app |
| 7 | CloudTrail enabled (all regions, log validation, encryption) |
| 8 | CloudWatch IAM Security Dashboard |
| 9 | CloudWatch Alarm for unauthorized API calls |
| 10 | SNS email alert configuration |

## 🧪 Skills Demonstrated

- ✅ IAM least privilege implementation
- ✅ MFA enforcement at organizational level
- ✅ Custom policy writing (JSON)
- ✅ Audit logging configuration (CloudTrail)
- ✅ Security monitoring & alerting (CloudWatch + SNS)
- ✅ AWS Free Tier cost management

## 📁 Repository Structure


## 💰 Cost Analysis

| Service | Monthly Cost (est.) |
|---------|--------------------|
| IAM | Free |
| CloudTrail | Free (1 copy) |
| S3 (logs) | ~$0.50 |
| CloudWatch | Free (first 10 metrics) |
| SNS | Free (first 1,000 publishes) |





