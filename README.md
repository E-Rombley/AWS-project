# AWS-project
Showcasing my aws DevOps project

# AWS Infrastructure Automation — Terraform + Kubernetes

Automated deployment of a full small business infrastructure on AWS. Write the config once, run it, and it's ready to use.

## What it does

Spins up a complete cloud infrastructure using Terraform to automate the deployment. Kubernetes manages the containers that simulate the full environment — networking, services, compute — everything a small business would need to run in the cloud.

## Why I built it

I wanted to understand how deep I could go with AWS while learning Terraform at the same time. Two birds, one stone. Rather than just following tutorials, I built something that actually resembles a real-world setup.

## How it works

- **Terraform** handles the AWS infrastructure — VPCs, subnets, security groups, EC2 instances, all defined as code
- **Kubernetes** runs the containerized workloads — a cluster of containers that simulate a full infrastructure stack
- Deploy the whole thing with one command, tear it down the same way

## Stack

- IaC: Terraform
- Container Orchestration: Kubernetes
- Cloud: AWS
- Target: Small business infrastructure simulation

## Usage

```bash
# Initialize Terraform
terraform init

# Preview what gets deployed
terraform plan

# Deploy the infrastructure
terraform apply

# Tear it down when done
terraform destroy
```

## What I learned

Terraform makes infrastructure reproducible — the same environment every time, no manual clicking around in the AWS console. Kubernetes showed me how containers talk to each other and how to manage them at scale. Combining both gave me a full picture of how modern cloud infrastructure actually works.

---

> Built to understand AWS and Terraform by doing, not just reading docs.
