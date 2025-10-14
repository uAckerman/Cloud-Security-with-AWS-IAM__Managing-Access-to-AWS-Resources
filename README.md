# Cloud Security with AWS IAM (Managing Access to AWS Resources)
Securing AWS resources by managing access with IAM policies, ensuring controlled permissions for users across different environments.

## Overview

This project focuses on **Cloud Security** using **AWS Identity and Access Management (IAM)** to control and manage access to AWS resources. AWS IAM allows administrators to define policies for users, groups, and roles to ensure that only authorized individuals have access to specific resources.

In this project, the objective was to demonstrate how IAM can be used to manage permissions effectively, focusing on tasks such as:

- **Setting Up EC2 instances** for different environments (production and development).
- **Onboarding a new intern** with controlled access to the development environment while restricting access to the production environment.
- **Testing IAM policies** to ensure that users can only access the resources they are authorized to use.

## Tools and Services Used

**Amazon EC2** : To provision virtual machines for both production and development environments.  
**AWS IAM (Identity and Access Management)**: To define user permissions and manage access control policies.

## Architecture Overview

**Production Environment**: A fully operational EC2 instance.  
**Development Environment:** A separate EC2 instance where the intern can safely experiment and test features without affecting the production environment.

## Methodology

1- Launching EC2 Instances
Launched two EC2 instances with the following configurations:

**Production Instance:**
Tagged with Env: production

**Development Instance:**
Tagged with Env: development

_Both instances were tagged to easily identify and separate them based on the environment._
