# Azure Data Engineering Automation: Terraform & CI/CD

This repository serves as an Infrastructure as Code (IaC) project focusing on orchestrating the provisioning of Azure services tailored for Data Engineering tasks using Terraform.

## Prerequisites
Before getting started, ensure you have the following prerequisites:

- Azure Account with an active subscription
- Azure CLI installed
- Terraform CLI installed
- Any preferred IDE such as Visual Studio Code or PyCharm

## System Architecture


## Getting Started
Follow these steps to begin using the project:

1. **Clone the Repository**: 
   Clone this repository to your local machine.

2. **Update terraform.tfvars**:
   Replace the content of the file named `terraform.tfvars` located in the root directory of the project with your specific configuration.

3. **Initialize Terraform**:
   Run the following command in the root directory of the project to initialize the Terraform project:
   ```
   terraform init
   ```

4. **Validate Terraform Code**:
   Ensure the Terraform code is valid by running:
   ```
   terraform validate
   ```

5. **Preview Changes**:
   Review the changes that will be applied by running:
   ```
   terraform plan
   ```

6. **Apply Changes**:
   Apply the changes to provision Azure services by running:
   ```
   terraform apply
   ```

With these steps, you can effectively manage and provision your Azure resources for Data Engineering tasks using Terraform.
