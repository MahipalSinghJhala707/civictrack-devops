flowchart LR
User --> Route53
Route53 --> ALB
ALB --> Ingress
Ingress --> Service
Service --> Pods
Pods --> RDS
GitHub --> CI/CD --> ECR --> EKS
