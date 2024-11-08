# Infrastructure Creation and Deploying a WEBSITE in AWS using Terraform

## Build, Deploy and Automate the deployment of a website in AWS using Terraform
I developed the entire project independently, without resorting to external Terraform modules. This approach allowed me to gain a deeper understanding of Terraform by manually managing all outputs, variables, and dependencies. Although it was challenging, the final product is fully operational.

## Real-World Considerations
In practice, utilizing modules from the Terraform registry is often favored, as they are well-tested and adhere to best practices. However, this exercise significantly enhanced my comprehension of Terraform's core concepts and underscored the value of pre-built modules.

## Implementation Details  

- Database Password: Securely stored in a local terraform.tfvars file and incorporated via the Terraform CLI during deployment.
- Webserver Installation: The install-wordpress.sh script for Amazon Linux 2023 effectively utilizes Terraform variables and operates as intended.

## Project Status
- Load Balancer: Fully operational and accessible.
- Target Groups: Healthy and successfully directing traffic to Auto Scaling Group instances.
- Bastion Host: Established connectivity to private subnet EC2 instances running WordPress.
- Instances & Database: All components are functioning smoothly.

## Conclusion
Thank you for reviewing my exam. This project has been an invaluable learning experience, and I am confident that the skills I have acquired will be beneficial in real-world applications.