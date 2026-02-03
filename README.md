🚀 CivicTrack Backend DevOps Deployment
📌 Overview

This project demonstrates a production-grade DevOps deployment of a Node.js backend using AWS EKS, Docker, and GitHub Actions CI/CD.

🏗 Architecture

AWS EKS (Kubernetes cluster)

Application Load Balancer (ALB)

Route53 DNS

PostgreSQL RDS

Docker containers

GitHub Actions CI/CD

ECR for container registry

⚙️ Tech Stack

Node.js

Express

Docker

Kubernetes

AWS EKS

AWS RDS

AWS ALB

Route53

GitHub Actions

Trivy (security scanning)

🔁 CI/CD Pipeline

Build Docker image

Scan with Trivy

Push image to ECR

Deploy to EKS

Rolling update

Optional DB migrations

🔐 Security

Secrets stored in Kubernetes Secrets

RDS SSL enabled

HTTPS via ACM certificate

Image scanning via Trivy

📦 Deployment Flow
GitHub Push → Build → ECR → EKS → ALB → Users

🧪 Features Implemented

Zero downtime deployment

Rolling updates

Health checks

Auto scaling ready

Secure DB connection

JWT auth backend

🧠 Key Learnings

Kubernetes networking

CI/CD automation

AWS IAM permissions

Ingress + ALB routing

Secret management