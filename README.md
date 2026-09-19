# AWS Data Engineering Projects

## Project 1: Amazon S3 Secure File Storage

### Services Used
- Amazon S3
- S3 Versioning
- S3 Server-Side Encryption (SSE-S3)
- S3 Lifecycle Rules

### What I Did
- Created a private S3 bucket
- Enabled Block Public Access
- Enabled versioning
- Enabled server-side encryption
- Created input, processed and archive folders
- Uploaded and downloaded files
- Tested file versioning
- Created a lifecycle rule for noncurrent versions

---

## Project 2: Amazon VPC Public and Private Network

### Services Used
- Amazon VPC
- Subnets
- Internet Gateway
- Route Tables
- Security Groups

### What I Did
- Created a VPC with CIDR `10.0.0.0/16`
- Created 2 public subnets
- Created 2 private subnets
- Created and attached an Internet Gateway
- Created public and private route tables
- Associated subnets with route tables
- Created Security Groups for ALB, App and DB

### Architecture Diagram
The VPC architecture diagram is included in this repository.
