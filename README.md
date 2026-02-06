# Azure Static Website using Terraform

This project demonstrates how to deploy an Azure Static Website using
Terraform by following Infrastructure as Code (IaC) principles.

The entire infrastructure is provisioned without using the Azure Portal,
making the deployment repeatable, version-controlled, and automated.

---

## Architecture Overview
- Azure Resource Group
- Azure Storage Account
- Static Website Hosting enabled on Storage Account
- Website content deployed using Terraform
- Public website URL exposed using Terraform outputs

---

## Terraform Concepts Used
- AzureRM Provider
- Variables and tfvars
- Resource dependencies
- Static website configuration
- Terraform outputs

---

## Prerequisites
- Azure Subscription
- Azure CLI installed and authenticated
- Terraform installed (v1.4+)

---

## How to Deploy

```bash
terraform init
terraform plan
terraform apply
