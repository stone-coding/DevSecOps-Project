
# DevSecOps-Project

This project demonstrates a practical DevSecOps pipeline integrating security and CI/CD best practices to deploy a Netflix-clone application on AWS.

## Key Features
- Infrastructure as Code: Terraform & Kubernetes on AWS EKS
- CI/CD Pipeline: Jenkins, SonarQube, Trivy, DockerHub
- Monitoring: Prometheus, Grafana
- ArgoCD for GitOps deployment
- Secured secrets via environment variables and credentials management
- Automated security scans (dependency, container image, code quality)

## Purpose
This repository is designed for learning, practicing, and showcasing practical skills in DevOps, Cloud Infrastructure, and Security Operations (DevSecOps).

## Cleanup Reminder
To avoid AWS charges, ensure you terminate:
- All EC2 instances
- EKS Node Groups
- EKS Control Plane (delete cluster)
- Related S3 buckets, IAM roles, CloudWatch logs, etc.

## License
For educational purposes only.
