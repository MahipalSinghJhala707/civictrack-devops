```mermaid
flowchart LR

Developer -->|Push Code| GitHub
GitHub -->|CI/CD| GitHubActions
GitHubActions -->|Build & Push| ECR
GitHubActions -->|Deploy| EKS

User --> Route53
Route53 --> ALB
ALB --> Ingress
Ingress --> Service
Service --> Pods
Pods --> RDS
```
