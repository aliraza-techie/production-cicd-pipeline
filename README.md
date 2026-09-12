# 🚀 Production CI/CD Pipeline with GitHub Actions

A production-focused CI/CD pipeline built with **GitHub Actions** to automate testing, security scanning, application builds, and deployments across **staging and production environments**.

The project demonstrates how a software delivery workflow can move from a GitHub code change through automated validation and controlled environment deployments.

---

## 📌 Project Overview

This project implements an automated CI/CD pipeline that runs whenever code is pushed to the `main` branch or a pull request targets `main`.

The pipeline automatically:

- Runs automated tests
- Performs a security audit
- Builds the application
- Deploys to a staging environment
- Runs a staging health check
- Deploys to a production environment
- Runs a production health check

### Pipeline Flow

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
Run Tests
    │
    ▼
Security Scan
    │
    ▼
Build Application
    │
    ▼
Staging Environment
    │
    ▼
Staging Health Check
    │
    ▼
Production Environment
    │
    ▼
Production Health Check
