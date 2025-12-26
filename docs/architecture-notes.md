# Architecture Notes

## Goal
Document a simple AWS setup and explain how core services work together in a business context.

## Services and Roles
### EC2 (Compute)
- Acts as a virtual server to run applications
- Common business use: hosting internal tools, web apps, batch processing jobs

### S3 (Storage)
- Object storage for files, logs, exports, backups, and datasets
- Common business use: storing reports, data exports, media assets, backups

### IAM (Security)
- Controls who can access AWS resources and what actions they can perform
- Principle of least privilege: grant only the permissions needed

### VPC (Networking)
- Defines network boundaries and connectivity
- Security groups act as a firewall for EC2 instances

## Security Considerations
- Avoid using root account for daily tasks
- Use strong passwords and MFA
- Limit public access to S3 buckets unless required
- Restrict inbound access to EC2 via security groups

## Next Steps
- Document a sample S3 bucket configuration (settings + access controls)
- Add a simple “cloud checklist” for setup and best practices
