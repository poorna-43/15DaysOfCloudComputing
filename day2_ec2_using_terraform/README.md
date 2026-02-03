# Day 2 – AWS EC2 Provisioning with Terraform

## Objective
Learn **Infrastructure as Code (IaC)** by provisioning an AWS EC2 instance using **Terraform**, replacing manual console setup with automated, repeatable code.

## Services Used
- Terraform: Infrastructure as Code
- AWS EC2: Virtual server provisioning

## Architecture
- Terraform code defines **EC2 instance** → deployed automatically to AWS
- IaC allows **repeatable, version-controlled, and automated deployments**

## Steps
1. Installed and configured **Terraform**
2. Configured AWS CLI for authentication
3. Wrote Terraform code (`main.tf`) to create an **EC2 instance**
4. Initialized Terraform: `terraform init`
5. Planned infrastructure changes: `terraform plan`
6. Applied configuration: `terraform apply` → EC2 instance created
7. Verified EC2 instance running in AWS Console

## Screenshots
<img width="1920" height="1080" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/50603612-60fa-4621-81eb-ba01d066705f" />
<img width="1920" height="1080" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/3dd037e3-c7e1-4002-87fa-fe877b907047" />
<img width="1920" height="1080" alt="Screenshot (66)" src="https://github.com/user-attachments/assets/547e3dd8-3ff3-4812-96b5-9b1c53e2b578" />
<img width="1920" height="1080" alt="Screenshot (67)" src="https://github.com/user-attachments/assets/f2879c7f-5372-4041-8ee5-07a71465c8b9" />
<img width="1918" height="777" alt="terraform" src="https://github.com/user-attachments/assets/f52d997b-bb4d-41fa-be09-5dfd6bab40c0" />
## Outcome
- Successfully automated EC2 provisioning
- Gained hands-on experience with *IaC workflow: init → plan → apply*
- First Terraform-managed cloud resource publicly verifiable
- Successfully automated EC2 provisioning
- Gained hands-on experience with **IaC workflow: init → plan → apply**
- First Terraform-managed cloud resource publicly verifiable
