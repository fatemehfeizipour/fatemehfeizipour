# Fatemeh Feizipour | AWS Cloud Engineer

I design and build secure, scalable AWS infrastructure — from network architecture and IAM to CI/CD pipelines and Infrastructure as Code.

🌐 **[View my full portfolio site →](https://main.d27jisummbpcj6.amplifyapp.com/)**

This repo is a supporting index of my project work. For the complete picture — experience, certifications, and all projects — see the site above.

---

## ☁️ Core Competencies

| Area | Tools / Concepts |
|---|---|
| Security & IAM | IAM policies, Security Groups, NACLs, least-privilege access |
| Networking | VPC design, subnetting, NAT Gateway, Bastion Host, route tables |
| Compute | EC2, Lambda |
| Storage | S3, VPC Gateway Endpoints |
| Databases | DynamoDB, RDS |
| Messaging | SQS, SNS (decoupled producer/consumer, pub-sub fan-out) |
| Scaling & Resilience | Load balancing, Auto Scaling, Multi-AZ architecture |
| CDN | CloudFront |
| Automation / CI-CD | GitHub Actions, AWS Amplify, Jenkins |
| Infrastructure as Code | Terraform, AWS CDK, CloudFormation |
| Monitoring & Cost | CloudWatch, resource auditing, cost optimization |

---

## 🚀 Featured Projects

### 🌐 Cloud-Native Portfolio Site
Built and deployed this portfolio site itself as a cloud project — a Next.js site hosted on AWS Amplify with a fully automated GitHub CI/CD pipeline (Provision → Build → Deploy → Verify), provisioned entirely through AWS CDK.
🔗 [Live site](https://main.d27jisummbpcj6.amplifyapp.com/) · [Code](https://github.com/fatemehfeizipour/Projects/blob/main/Nextjs-portfolio-amplify-project/README.md)

### 💰 AWS Cost & Resource Auditor
Read-only CLI tool that scans an AWS account for common sources of wasted spend — unattached EBS volumes, idle EC2 instances (via CloudWatch CPU metrics), S3 buckets missing lifecycle policies, and unused Elastic IPs. Built with Python and boto3, with paginated API calls and fail-safe error handling per check.
🔗 [Walkthrough video](https://www.linkedin.com/posts/fatemeh-feyzipour_aws-python-boto3-activity-7489349478773260288-vzou) · [Code](https://github.com/fatemehfeizipour/Projects/tree/main/Cost-auditor-script)

### 🔒 Highly Available Multi-AZ VPC
Designed and deployed a highly available AWS VPC as code with Terraform, spanning two Availability Zones with public and private subnets, NAT Gateways, an Internet Gateway, and full route table configuration.
🔗 [Code](https://github.com/fatemehfeizipour/Projects/tree/main/terraform-portfolio-project/terraform-VPC)

### 🛡️ Secure VPC Redesign for an Invoicing App
Redesigned the network architecture for an invoicing application handling bank details for ~8,000 users — moved from a fully public setup to a defense-in-depth VPC with public/private/isolated subnet tiers, security group chaining, AWS Systems Manager Session Manager in place of SSH, and invoice files moved to S3 behind a VPC Gateway Endpoint.
🔗 [Case study](https://www.linkedin.com/posts/fatemeh-feyzipour_aws-cloudsecurity-terraform-activity-7484165129354506240--UOa)

### 🚪 Bastion Host Access Architecture
Designed a secure administrative access pattern across two Availability Zones — SSH to a bastion host in the public subnet, then SSL to private EC2 instances — keeping private resources fully unreachable from the internet, with full public/private route table mapping.
🔗 [Case study](https://www.linkedin.com/posts/fatemeh-feyzipour_aws-cloudcomputing-cloudengineering-activity-7480596205891186688-wN3r)

### 🌍 Static Website on S3 + CloudFront with Terraform
Built and deployed a static website using Amazon S3 for storage and Amazon CloudFront for global content delivery, exploring multilayer S3 security.
🔗 [Code](https://github.com/fatemehfeizipour/Projects/blob/main/terraform-portfolio-project/terraform-nextjs-blog/README.md)

### 🏗️ Infrastructure as Code with CloudFormation
Designed and deployed AWS infrastructure using CloudFormation, including VPCs, subnets, EC2, IAM, Auto Scaling Groups, Load Balancers, and NAT Gateways.
🔗 [Code](https://github.com/fatemehfeizipour/Projects/tree/main/cloudformation-projects)

### 🎬 A Video Sharing Platform — System Design
Designed the architecture for a video-sharing platform covering the full upload-to-playback pipeline: S3 and Lambda for transcoding into multiple resolutions, Amazon Rekognition for content moderation, DynamoDB for metadata, API Gateway for auth and rate limiting, and CloudFront for low-latency delivery.
🔗 [Case study](https://www.linkedin.com/posts/fatemeh-feyzipour_aws-cloudcomputing-systemdesign-activity-7477097594838523904-M5F4)

### 🏛️ Traditional vs. Serverless Architecture
Compared three architectural approaches for a scalable web application — horizontal scaling, vertical scaling, and a fully serverless design with API Gateway, Lambda, and EventBridge — weighing trade-offs in scalability, resilience, latency, and cost.
🔗 [Case study](https://www.linkedin.com/posts/fatemeh-feyzipour_aws-cloudcomputing-systemdesign-activity-7477097594838523904-M5F4)

### 📨 Asynchronous Messaging with SQS + SNS
Implemented a decoupled order-processing pattern: producer publishes messages to an SQS queue, a consumer processes and deletes them via long polling, with SNS fan-out for downstream notifications. Demonstrates async processing and loose coupling between services.
🔗 [Code](https://github.com/fatemehfeizipour/Projects/tree/main/aws-sqs-project)

---

## 📂 Repositories

- 🧪 [`AWS-Learning-Lab`](https://github.com/fatemehfeizipour/AWS-Learning-Lab) — infrastructure builds and practice environments
- 💼 [`Projects`](https://github.com/fatemehfeizipour/Projects) — full project implementations
- 📝 [`Documentation`](https://github.com/fatemehfeizipour/Documentation) — technical notes and reference material

---

## 📫 Contact

- Portfolio: [main.d27jisummbpcj6.amplifyapp.com](https://main.d27jisummbpcj6.amplifyapp.com/)
- LinkedIn: [linkedin.com/in/fatemeh-feyzipour](https://www.linkedin.com/in/fatemeh-feyzipour/)
- GitHub: [github.com/fatemehfeizipour](https://github.com/fatemehfeizipour)
- Email: fatemehfeizipur@gmail.com
