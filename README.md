# Terraform Proof of Concept

This project demonstrates the deployment and management of several AWS services using **Terraform**. The entire infrastructure is managed through **Terraform Cloud** and integrated with **GitHub VCS** for version control and automated deployments. The purpose of this proof of concept (PoC) is to showcase the use of Infrastructure as Code (IaC) to automate the provisioning and management of cloud resources.

## Project Overview

In this PoC, I used Terraform to define, deploy, and manage multiple AWS services, and I leveraged Terraform Cloud to handle the state management and automation of the deployment process. GitHub is integrated with Terraform Cloud for version control and continuous integration/continuous deployment (CI/CD) pipelines.

### Key Features

- **Infrastructure as Code (IaC):** All AWS services are defined using Terraform configuration files, allowing for repeatable, scalable, and automated infrastructure provisioning.
- **Terraform Cloud:** Terraform Cloud is used to manage state files and automate the deployment process.
- **GitHub VCS Integration:** Changes to the infrastructure are tracked in a GitHub repository and automatically applied via Terraform Cloud workflows.
- **Modular Terraform Configurations:** The Terraform configurations are modular, ensuring reusability and ease of maintenance.

## AWS Services Deployed

The following AWS services were deployed in this project:

- **Amazon S3:** For object storage, used for storing static assets.
- **Amazon EC2:** Provisioned virtual machines with various configurations.
- **Amazon RDS:** Managed relational database instances.
- **Amazon VPC:** Configured virtual private cloud for networking.
- **Amazon IAM:** Managed AWS Identity and Access Management (IAM) roles and policies.

## Tools and Technologies

- **Terraform**: Infrastructure as Code (IaC) tool used to provision AWS services.
- **Terraform Cloud**: Used for state management, collaboration, and automation.
- **GitHub**: Version control system for tracking and managing code changes.
- **AWS**: Cloud provider where the services are deployed.
