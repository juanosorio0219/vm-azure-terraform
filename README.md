# Azure Virtual Machine Creation Project with Terraform

This is a mini project that utilizes Terraform to create a virtual machine (VM) in Azure.

## Project Description

The objective of this project is to provide a basic Terraform configuration to create a virtual machine in Azure. The virtual machine will be created using the Ubuntu 22.04 LTS image from Canonical.

## Project Structure

The project contains the following files:

- `vm.tf`: This file contains the main Terraform configuration to create the virtual machine in Azure.
- `versions.tf`: In this file, the versions of Terraform providers to be used in the project are specified.

## Prerequisites

Before getting started, ensure that you have the following:

- An Azure account with access to the Azure Portal.
- Terraform installed on your local system. You can download it from the [Terraform website](https://www.terraform.io/downloads.html).
- Azure credentials configured in your local environment. You can configure them using Azure CLI or by providing the necessary environment variables.

## Usage

1. Clone this repository to your local system:\
**git clone https://github.com/juanosorio0219/vm-azure-terraform.git**

2. Change into the project directory:\
**cd vm-azure-terraform**

3. Initialize the Terraform project:\
**terraform init**

4. Review and adjust the configuration in the `vm.tf` file as needed.

5. Run `terraform plan` to preview the changes Terraform will make:\
**terraform plan**

6. If the plan looks good, apply the configuration to create the virtual machine:\
**terraform apply**

7. Once the virtual machine is successfully created, you can access it using SSH or other methods as per your configuration.

8. When you no longer need the virtual machine, you can destroy it by running:\
**terraform destroy**










