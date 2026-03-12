# Cloud Security Audit Project 
## Description
This project demonstrates a security audit for aws infrastructure as Code (Terraform).
## Tools Used :
- **Checkov**: Static Code Analysis (SCA) to detect misconfigurations.
- **Terraform**: To define and remediate cloud resources.
- ## Steps Performed:
- 1. Analyzed S3 bucket configurations.
  2. Identified missing encryption and versioning  (CKV_AWS_19 , CKV_AWS_21).
  3. Remediated the vulnerabilities by uupdating the Terraform code.
  
