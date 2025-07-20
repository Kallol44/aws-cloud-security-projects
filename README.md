# AWS Cloud Security Projects

This repository contains hands-on AWS cloud security projects

## Project 1: AWS Security Monitoring & Alerting

**Description:**
A comprehensive project simulating a real-world attack (public S3 exposure) and building a detection and response pipeline using native AWS services.

**Key Features:**

* S3 Bucket misconfiguration (simulated attack)
* AWS CloudTrail & AWS Config setup
* AWS GuardDuty threat detection
* EventBridge rules to detect GuardDuty findings
* SNS email alerts to notify on threats
* Architecture diagram & screenshots included

**Folder:** `project1_aws_security_monitoring`

**GitHub Link:** [aws-security-monitoring](https://github.com/Kallol44/aws-security-monitoring)


## Project 2: AWS VPC App Deployment + CSPM Scan (Prowler)

**Description:**
This project demonstrates deploying a simple application inside a VPC, and then performing a Cloud Security Posture Management (CSPM) scan using Prowler to detect misconfigurations and compliance violations.

**Key Features:**

* Manual creation of VPC, subnets, route tables, and security groups
* Deployment of EC2 instance with NGINX web server
* CSPM scan using open-source tool Prowler
* Python-based Prowler execution and report generation (HTML, JSON)

**Folder:** `project2_aws_vpc_cspm_prowler`

## How to Use

1. Explore each project folder
2. Open the respective `README.md` file
3. Review architecture diagram (in `/docs`)
4. View screenshots for step-by-step actions (in `/screenshots`)


## Author

**Kallol Das**

* [LinkedIn Profile](https://www.linkedin.com/in/kallola-das-6aa28181/)
* AWS Security Certified | CCSK | SAP Basis Expert


## License

This repository is licensed under the [MIT License](LICENSE).
