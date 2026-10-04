# MERN Application Orchestration & Scaling on AWS EKS

This repository contains the complete infrastructure, CI/CD pipeline, Helm deployment charts, and monitoring configuration for deploying the **StreamingApp** MERN stack to Amazon EKS.

---

## 🏗️ System Architecture

1. **Version Control**: GitHub (`pandeysmitasuchi-pixel/Orchestration`).
2. **CI/CD**: Jenkins running pipeline jobs triggered on new Git pushes.
3. **Container Registry**: Amazon ECR hosting `streaming-frontend` and `streaming-backend`.
4. **Orchestration**: AWS EKS cluster running Helm-packaged deployments.
5. **Monitoring & Logging**: AWS CloudWatch Container Insights and CloudWatch Logs.

---

## 🚀 Step-by-Step Deployment Instructions

### 1. AWS & CLI Configuration
Ensure your terminal environment on your **MacBook (owned by Suchismita)** is configured with AWS credentials:
```bash
aws configure
