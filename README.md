# Cloud Automation Portfolio

A collection of hands-on cloud automation projects demonstrating infrastructure as code, configuration management, and AWS resource provisioning.

## Projects

### 1. [Terraform VPC & EC2 Deployment](https://github.com/Metsam237/terraform-vpc-aws-project1)
Automated deployment of an AWS VPC, subnet, security group, and EC2 instance using modular Terraform.
- **Stack:** Terraform, AWS (VPC, EC2, SG, IGW)
- **Highlights:** Modular architecture, GitHub Actions CI/CD, parameterized variables

### 2. [Web Server Deployment with Terraform & Ansible](https://github.com/Metsam237/terraform-ansible-vpc-aws-project2)
Deploys 3 Nginx web servers on AWS using Terraform for provisioning and Ansible for configuration management.
- **Stack:** Terraform, Ansible, AWS (VPC, EC2 x3, SG, IGW)
- **Highlights:** Terraform + Ansible integration, dynamic inventory generation, multi-instance deployment

### 3. [Multi-AZ Web Infrastructure](https://github.com/Metsam237/terraform-multi-az-web-infra)
Production-style deployment with RHEL 8 instances across multiple availability zones running Apache httpd.
- **Stack:** Terraform, AWS (VPC, EC2 x2, multi-AZ subnets, SG)
- **Highlights:** Multi-AZ architecture, RHEL AMI, split Terraform files (networking/compute/security)

## Skills Demonstrated
- **Infrastructure as Code** — Terraform modules, state management, CI/CD validation
- **Configuration Management** — Ansible playbooks, dynamic inventory
- **AWS Networking** — VPC design, subnets, route tables, internet gateways, security groups
- **DevOps Practices** — Git version control, GitHub Actions, modular code structure

## About
These projects were built as part of a cloud automation and DevOps learning path. Each project progressively builds on the previous one, demonstrating increasing complexity and real-world patterns.

---
Built by [Metsam237](https://github.com/Metsam237)
