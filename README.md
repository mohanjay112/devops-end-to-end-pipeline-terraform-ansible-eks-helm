#  DevOps End-to-End Project: CI/CD with Jenkins, Ansible, Terraform, EKS & Helm

This project demonstrates a full CI/CD pipeline integrating multiple DevOps tools — from source code to deployment and monitoring.

# Tools Used
- Version Control: Git, GitHub
- Build & CI/CD: Jenkins, Maven, Jenkinsfile
- Static Code Analysis: SonarQube
- Artifact Repository: JFrog Artifactory
- Containerization: Docker
- Configuration Management: Ansible
- Infrastructure as Code: Terraform
- Orchestration & Deployment: AWS EKS (Kubernetes), Helm
- Monitoring: Prometheus, Grafana

---

# Modules

# 1. **Terraform Setup**
- Provision EC2, VPC, Security Group
- Create EKS Cluster
- Store state in S3

# 2. **Ansible Playbooks**
- Install Jenkins, Maven, Docker on EC2
- Setup Jenkins master-slave configuration

# 3. **Jenkins Pipeline**
- Build Java App
- Run SonarQube Quality Gate
- Publish Artifact to JFrog
- Create Docker image and push to JFrog
- Deploy on EKS using Helm

# 4. **Monitoring Stack**
- Prometheus and Grafana setup on Kubernetes
- Dashboards for app and infra monitoring

