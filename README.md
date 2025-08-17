# 🚀 DevOps Project: Azure Databricks CI/CD Pipeline with Azure DevOps

## 📖 About
This project demonstrates how to build and deploy a **CI/CD pipeline** for Azure Databricks using **Azure DevOps**.  
The pipeline automates the deployment of Databricks notebooks from a **development environment** to a **production environment**, ensuring reliability, scalability, and faster delivery of data workflows.

---

## 🛠 Skills Demonstrated
- Azure Cloud Services (Resource Groups, Databricks, Managed Identity)
- Azure DevOps (Pipelines, Repos, Service Connections, Environments)
- Continuous Integration & Continuous Deployment (CI/CD)
- Infrastructure as Code (YAML pipeline templates, scripts)
- Source Control & Branching Strategies (Feature Branch, PR, Main Protection)
- Automation using PowerShell & YAML
- Data Engineering Workflow Management in Databricks

---

## 🎯 Objective
- To establish a **robust CI/CD pipeline** for Databricks notebooks.  
- To maintain a **single source of truth** by using a `/live` folder in the Dev workspace.  
- To ensure **seamless deployment** of notebooks from Dev → Prod with minimal manual intervention.  
- To improve collaboration, governance, and efficiency in data engineering projects.

---

## ✅ Advantages
- **Automation**: Eliminates manual deployment, reducing errors.  
- **Scalability**: Works across multiple environments (Dev, Test, Prod).  
- **Collaboration**: Enforces PR-based workflow for team development.  
- **Governance**: Branch policies secure the `main` branch.  
- **Traceability**: Every deployment is tracked through Azure DevOps pipelines.  
- **Reusability**: Modular templates (`deploy-notebooks.yml`, scripts) can be reused across projects.

---

## 🔮 Future Work
- Integrate **unit testing** for notebooks before deployment.  
- Extend pipeline to include **data quality checks** and **linting**.  
- Add **multi-region deployments** for high availability.  
- Incorporate **monitoring and alerting** (Azure Monitor, Log Analytics).  
- Enable **rollback mechanisms** in case of failed deployments.  
- Integrate with **Terraform** or **Bicep** for complete infrastructure automation.

---

## 📌 Step-by-Step Setup
For detailed setup instructions, refer to [AzureDatabricks-CI-CD-Runbook-v1.0](AzureDatabricks-CI-CD-Runbook-v1.0).

---

👨‍💻 Built with **Azure DevOps** and **Databricks** for end-to-end automation.
