# Day 2 Submission

## Personal Information
- **Name:** Stephen Mugo
- **Date:** 4th June 2025
- **GitHub Username:** stephmugo

## Task Completion
- [x] Read Chapter 2 of "Terraform: Up & Running" (Setting Up Your AWS Account & Installing Terraform)
- [x] Completed Required Hands-on Labs
  - [x] Lab 01: Setup your AWS Account (if needed)
  - [x] Lab 02: Install AWS CLI
  - [x] Lab 03: Installing Terraform and set up Terraform with AWS
- [x] Set up AWS account
- [x] Install Terraform locally
- [x] Install and configure AWS CLI
- [x] Install Visual Studio Code (VSCode) and add the AWS plugin
- [x] Configure VSCode to work with AWS

## Setup Validation

### Terraform Installation
- **Version:** Terraform v1.11.4
- **Installation Method:** choco install terraform
- **Path:** /c/ProgramData/chocolatey/bin/terraform

### AWS CLI Configuration
- **Version:** aws-cli/2.27.11 Python/3.13.3 Windows/11 exe/AMD64
- **Default Region:** us-east-1
- **Profile Configuration:** 1

### VSCode Configuration
- **Extensions Installed:** amazonwebservices.aws-toolkit-vscode
hashicorp.terraform
- **AWS Plugin Status:** Configured

## Configuration Files
Please place your configuration screenshots and validation files in the `setup-validation` folder:
- `terraform-version.txt` - Output of `terraform version`
- `aws-config-validation.txt` - Output of `aws sts get-caller-identity` (sanitized)
- `vscode-extensions.png` - Screenshot of installed extensions

## Time Spent
- Reading: [1.5 hours]
- AWS Account Setup: [0.2 hours]
- Terraform Installation: [0.1 hours]
- AWS CLI Configuration: [0.1 hours]
- VSCode Setup: [0.1 hours]
- Total: [2 hours]

## Repository Structure
```
Day2/
└── Submissions/
    └── [Your GitHub Username]/
        ├── setup-validation/
        │   ├── terraform-version.txt
        │   ├── aws-config-validation.txt
        │   └── vscode-extensions.png
        └── submission_template_day2.md
```

## Setup Validation Commands
Document the commands you used to validate your setup:

```bash
# Terraform validation
terraform version
terraform providers

# AWS CLI validation  
aws --version
aws sts get-caller-identity
aws configure list

# VSCode validation
code --version
code --list-extensions | grep -E "(aws|terraform)"
```



