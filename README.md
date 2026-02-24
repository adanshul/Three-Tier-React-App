# Three-Tier-React-App

# 🚀 Three Tier React Application with DevSecOps, Terraform, Jenkins and Kubernetes

This project demonstrates how to build, deploy, and secure a modern cloud-native three-tier application using DevSecOps principles. The goal of this repository is to simulate a real-world environment where security is integrated across the entire Software Development Life Cycle (SDLC).

This project focuses on automation, infrastructure as code, CI/CD pipelines, containerization, and Kubernetes security while following secure development and deployment practices.

---

## 📌 Architecture Overview

This application follows a three-tier architecture:

1. Frontend – React web application  
2. Backend – API layer  
3. Database – Persistent storage  

The application is containerized and deployed on Kubernetes, with automated provisioning and CI/CD.

---

## ⚙️ Technologies Used

### Cloud and Infrastructure
- Terraform  
- Infrastructure as Code  
- Automated resource provisioning  

### CI/CD and Automation
- Jenkins  
- GitHub  
- Continuous Integration and Continuous Deployment  

### Containers and Orchestration
- Docker  
- Kubernetes  
- Kubernetes manifests  

### Security and DevSecOps
- Static Application Security Testing  
- Software Composition Analysis  
- Dynamic Application Security Testing  
- Container security  
- Infrastructure security scanning  
- Secrets management  
- Policy as Code  

---

## 🏗️ Project Structure

```text
Three-Tier-React-App/
├── Application-Code/
│   ├── frontend/
│   ├── backend/
│   └── database/
├── Jenkins-Pipeline-Code/
│   └── (CI/CD pipeline definitions)
├── Jenkins-Server-TF/
│   └── (Terraform code for provisioning Jenkins)
└── Kubernetes-Manifests-file/
    └── (Kubernetes deployments and services)
```

---

## 🔐 DevSecOps Approach

This project integrates security throughout the development lifecycle instead of treating security as a final step.

---

### 1. Static Application Security Testing (SAST)

Static security testing is performed during the build phase to identify vulnerabilities early in development.

Focus areas:
- Injection vulnerabilities  
- Insecure coding practices  
- Hardcoded credentials  
- Authentication and authorization issues  

This helps shift security left and reduces the cost of fixing vulnerabilities later.

---

### 2. Software Composition Analysis (SCA)

This project includes dependency analysis to detect vulnerable open-source libraries used in the application.

Benefits:
- Reduces supply chain risk  
- Helps keep dependencies updated  
- Automates vulnerability detection  

---

### 3. Dynamic Application Security Testing (DAST)

After deployment to a test environment, automated scans simulate real attacker behavior.

Focus areas:
- Authentication and session management  
- API security  
- Input validation  
- Runtime vulnerabilities  

This validates security controls in a real environment.

---

### 4. Container and Image Security

Container images are scanned before deployment to ensure they are secure.

Focus areas:
- Vulnerable packages  
- Outdated base images  
- Software supply chain risks  

This helps prevent vulnerable workloads from running in production.

---

### 5. Infrastructure Security

Infrastructure as Code is scanned before deployment to detect misconfigurations.

Focus areas:
- Open ports  
- Weak permissions  
- Publicly exposed resources  
- Encryption and security best practices  

This ensures secure and consistent infrastructure provisioning.

---

### 6. Kubernetes Security

Security controls are implemented to protect the runtime environment.

Key practices:
- Least privilege access  
- Secure pod configurations  
- Non-root containers  
- Network segmentation  
- Restricted communication between tiers  
- Secure service accounts  

These controls reduce the attack surface and improve resilience.

---

### 7. Secrets Management

Sensitive information is never stored in source code.

Approach:
- Secure storage of secrets  
- Runtime secret injection  
- Rotation and monitoring  
- Environment-based configuration  

This prevents credential leakage and improves operational security.

---

## 🔄 CI/CD Workflow

The CI/CD pipeline automates the following:

1. Code checkout  
2. Dependency installation  
3. Static security scanning  
4. Dependency vulnerability scanning  
5. Build and unit testing  
6. Container image creation  
7. Container security scanning  
8. Deployment to Kubernetes  
9. Dynamic security testing  
10. Continuous monitoring and validation  

This ensures that security is enforced at every stage of the deployment process.

---

## 🎯 Key Security Outcomes

- Security integrated into development and deployment  
- Automated vulnerability detection  
- Reduced manual effort  
- Faster and more secure releases  
- Improved visibility and monitoring  
- Real-world DevSecOps implementation  

---

## 📚 Learning Objectives

This project helped me gain hands-on experience in:

- Cloud and Infrastructure as Code  
- Secure CI/CD pipeline design  
- Kubernetes and container security  
- Application and API security  
- Threat detection and prevention  
- Automation and monitoring  
- Secure development practices  

---

## 🚀 Future Improvements

- Implement GitOps deployment  
- Add runtime threat detection  
- Integrate centralized logging and monitoring  
- Implement zero-trust architecture  
- Add automated compliance checks  
- Enhance policy enforcement  

---

## 🤝 Contributing

Contributions are welcome. Please open an issue or submit a pull request for improvements.

---

## 📄 License


This project is licensed under the MIT License.

