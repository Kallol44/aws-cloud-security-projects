# Phase 2: Cloud Security Posture Management (CSPM) Scan with Prowler

This phase uses **Prowler**, an open-source security tool, to scan your AWS environment for misconfigurations and compliance violations.

### 🔍 Key Steps:

- Install Python and dependencies
- Clone **Prowler GitHub repo**
- Run CSPM scan using:
  ```
  python prowler-cli.py aws -M html
  ```
- Review generated **HTML** and **JSON** reports

### 📋 What It Checks:

- IAM best practices
- S3 bucket permissions
- CloudTrail logging
- GuardDuty status
- Root account usage
- CIS Benchmarks, NIST, ISO, and more

### 🎯 Objective

To gain visibility into your AWS security posture and identify areas for improvement using industry-aligned benchmarks.
