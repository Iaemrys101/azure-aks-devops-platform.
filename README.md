# Azure Kubernetes DevOps Project

This project demonstrates the deployment of a containerised web application to Microsoft Azure using Terraform, Docker, Azure Container Registry (ACR), Azure Kubernetes Service (AKS), GitHub Actions, Prometheus, and Grafana.

The project was built as a hands-on Platform Engineering and DevOps exercise, covering Infrastructure as Code, containerisation, Kubernetes orchestration, CI/CD automation, cloud authentication, RBAC, and monitoring.

## Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Azure | Cloud platform |
| Terraform | Infrastructure as Code |
| Azure Kubernetes Service (AKS) | Kubernetes cluster |
| Azure Container Registry (ACR) | Docker image registry |
| Docker | Application containerisation |
| Nginx | Web server |
| Kubernetes | Container orchestration |
| GitHub | Source control |
| GitHub Actions | CI/CD automation |
| OpenID Connect (OIDC) | Passwordless GitHub-to-Azure authentication |
| Azure RBAC | Cloud access control |
| Helm | Kubernetes package management |
| Prometheus | Metrics collection and monitoring |
| Grafana | Metrics visualisation |
| Alertmanager | Monitoring alerts |

## Infrastructure

The Azure infrastructure is provisioned using Terraform.

The environment includes:

- Azure Resource Group
- Virtual Network
- AKS Subnet
- Azure Container Registry
- Azure Kubernetes Service
- Azure RBAC role assignments

The AKS cluster uses a dedicated subnet within the Azure Virtual Network.

Terraform manages the infrastructure lifecycle and maintains state to track the relationship between the Terraform configuration and resources deployed in Azure.<img width="983" height="715" alt="Screenshot 2026-09-14 071609" src="https://github.com/user-attachments/assets/5266905a-99c0-458f-9066-b558c8fe2a9e" />
<img width="1238" height="736" alt="Screenshot 2026-09-14 071514" src="https://github.com/user-attachments/assets/67153057-e29e-4f79-bf38-57c6c1efdcf4" />
<img width="1408" height="795" alt="Screenshot 2026-09-14 071429" src="https://github.com/user-attachments/assets/39a0bdfa-9d1b-4eb0-a85d-3d9cf8b50d7f" />
<img width="1572" height="661" alt="Screenshot 2026-09-14 070201" src="https://github.com/user-attachments/assets/9670d19a-19a6-400d-8926-9927b7047d98" />
<img width="1915" height="907" alt="Screenshot 2026-09-14 070033" src="https://github.com/user-attachments/assets/9e856fd4-aa25-45a0-a6fe-29f2a15632c5" />
<img width="1912" height="960" alt="Screenshot 2026-09-14 065924" src="https://github.com/user-attachments/assets/950b1df4-6951-4ed9-a7d3-dea4429cb02d" />
<img width="2207" height="1287" alt="Screenshot 2026-09-14 064701" src="https://github.com/user-attachments/assets/fcfa3838-0eb7-46fc-968c-3e27491d3cac" />
<img width="1916" height="1070" alt="Screenshot 2026-09-14 064618" src="https://github.com/user-attachments/assets/92393699-a4b4-4272-98e8-2c32bc70c777" />
