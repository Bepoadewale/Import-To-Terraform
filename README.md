# Requirements

1. AWS CLI installed.
2. Terraform installed.
3. AWS credentials configured.
4. Terraform initialized.
5. For the manual.tf - Use "terraform import aws_instance.compute1 instanceID" in terminal to import the EC2 instance. 
6. For the manual.tf - Use "terraform import aws_security_group.compute1-sg securitygroupID" in terminal to import the security group.
7. Use "terraform state list" to see imported resources.
