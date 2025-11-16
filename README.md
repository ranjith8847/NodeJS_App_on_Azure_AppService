# Azure_app_deployment_documentation
the repo shows Deploying a Node.js Application to Azure App Service Using Azure DevOps
Also covers basic components of Azure and the steps to deploy those.

## 📌 Overview

This repository provides a step-by-step guide to deploy a Node.js application into *Azure App Service using Azure DevOps (ADO)* with a *self-hosted agent*.  
It includes configuring infrastructure, connecting the CI/CD pipelines, and routing traffic through Azure Front Door.

This guide is designed for developers learning Azure deployments hands-on or setting up a production-ready deployment flow.

## 🏆 What This Project Demonstrates

By following this documentation, you show real-world expertise in:

✔ **Azure Cloud**  
✔ **Azure DevOps CI/CD**  
✔ **VM configuration + Linux**  
✔ **Self-Hosted Agent setup**  
✔ **PostgreSQL Flexible Server**  
✔ **App Service Deployment**  
✔ **Node.js Production Build**  
✔ **Global routing with Azure Front Door**  
✔ **Enterprise-grade deployment flow** 

## 🧱 Architecture Components

This deployment uses the following Azure resources:

| Component                | Purpose                                         |
|--------------------------|-------------------------------------------------|
| **Resource Group**       | Logical grouping for all Azure resources        |
| **PostgreSQL Flexible Server** | Application database with HA/DR capabilities |
| **Virtual Machine (VM)** | Acts as the self-hosted agent for Azure DevOps  |
| **App Service**          | Hosts the Node.js application                   |
| **Azure Front Door**     | Global load balancing + routing                 |
| **Azure DevOps Pipelines** | CI/CD pipeline for automated build & release |

