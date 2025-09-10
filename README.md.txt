# Cloud-Ready SaaS App

## Project Overview
Mini SaaS application deployed to AWS with infrastructure-as-code using Terraform. Demonstrates CI/CD, auto-scaling, and monitoring for cloud-native apps.

## Tech Stack
- Python Flask / Java Spring Boot
- AWS EC2, S3, Lambda, RDS
- Terraform for IaC
- GitHub Actions for CI/CD
- Docker

## Features
- CRUD operations via REST APIs
- Cloud deployment with Terraform
- CI/CD pipeline for automated build & deploy
- Auto-scaling and monitoring using AWS CloudWatch

## Metrics
- Deployment time via CI/CD: < 5 minutes
- Auto-scaling triggers: CPU > 70%
- Logs aggregated & monitored in CloudWatch

## Architecture Diagram
[Client] --> [Flask API / Spring Boot] --> [RDS DB]
|--> [S3 Storage]
|--> [Lambda Functions]


## How to Run
1. Clone repo
2. Run Terraform scripts: `terraform init && terraform apply`
3. Deploy app via CI/CD workflow

## Key Learnings
- Cloud deployment & infrastructure as code
- CI/CD pipeline setup
- Auto-scaling & monitoring in AWS
