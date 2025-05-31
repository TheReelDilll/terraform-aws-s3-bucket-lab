# ☁️ Terraform Lab 3 — S3 Bucket with Versioning & Encryption

## 📚 Overview
Deployed an AWS S3 bucket from scratch using Terraform. Enabled versioning, applied server-side encryption, and validated that the infrastructure was secure, scalable, and ready for production workflows. Cleanly destroyed the environment after testing to stay cost-effective.

---

## 🛠️ Technologies Used
- **Terraform** (v1.3.0+)
- **AWS S3** (Simple Storage Service)
- **Server-Side Encryption** (SSE-S3)
- **Versioning** (for object recovery & tracking)
- **Terraform CLI** (for `init`, `apply`, `destroy`)

---

## 🧱 Key Features
- Created a secure and scalable **S3 bucket**
- Enabled **object versioning** to protect against overwrites and deletions
- Applied **SSE-S3 encryption** for data at rest
- Used Terraform best practices for clean, repeatable deployments

---

## ⚙️ Deployment Steps
1. Defined the bucket configuration in `main.tf`
2. Declared input variables in `variables.tf`
3. Supplied actual values in `terraform.tfvars`
4. Ran `terraform init` to initialize the working directory
5. Ran `terraform apply` to deploy infrastructure
6. Validated bucket in AWS Console
7. Ran `terraform destroy` to clean up resources

---

## 📂 Project Structure

```bash
terraform-lab-3-s3-bucket/
├── main.tf
├── variables.tf
├── terraform.tfvars
├── outputs.tf
├── README.md
