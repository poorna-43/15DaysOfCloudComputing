# Day 1 – Secure AWS Environment & Static Website

## Objective
Build a secure AWS environment and deploy first live static website.

## Services Used
- IAM: Users, Groups, Roles, MFA
- S3: Static website hosting

## Architecture
- IAM Users & Groups → Secure access  
- S3 Bucket → Public static site  

## Steps Performed
1. Created IAM group `Admins` with `AdministratorAccess`
2. Created IAM user `cloud-admin` with MFA
3. Generated programmatic access keys
4. Created S3 bucket and uploaded index.html
5. Enabled static website hosting

## IAM Permissions Overview

### Admin User
- Full access to AWS services
- MFA enabled for additional security
- Used for infrastructure management

### Restricted S3 User
- Read-only access to a specific S3 bucket
- No access to EC2, IAM, or other AWS services
- Demonstrates least-privilege principle

## Screenshots
<img width="1920" height="1080" alt="Screenshot (59)" src="https://github.com/user-attachments/assets/ce6a9a10-54a8-4427-86e4-e2e2f0a9425f" />
<img width="1920" height="1080" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/0cad92c6-49ef-4ac8-9b81-b2ef44f0d222" />
<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/ead68650-b93a-49e0-8cbd-98cbe02d0471" />




## Outcome
- Secure AWS environment with IAM best practices
- Successfully hosted a live static website on Amazon S3
- Gained hands-on experience with AWS security fundamentals
