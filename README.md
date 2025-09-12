 AWS VPC and Web Server Project

 Overview
In this project, I created a Virtual Private Cloud (VPC) on AWS to understand the basics of networking and web hosting in the cloud.  
The setup included one public subnet and one private subnet. A Windows server was launched in the public subnet with IIS installed to host a sample website, while an Ubuntu server was placed in the private subnet for isolation.

---

 Architecture
- One VPC  
- Public subnet → Windows EC2 instance with IIS web server  
- Private subnet → Ubuntu EC2 instance  
- Internet Gateway attached to allow external access  
- Security groups to control traffic  

[Architecture Diagram](images/vpc-architecture.png)


---

 AWS Services Used
- VPC  
- Subnets (public and private)  
- EC2 (Windows and Ubuntu)  
- Internet Gateway  
- Security Groups  



 Steps I Followed
1. Created a custom VPC with a CIDR block.  
2. Added a public subnet and a private subnet.  
3. Configured route tables and attached an internet gateway.  
4. Launched a Windows EC2 instance in the public subnet and installed IIS.  
5. Deployed a sample website on the IIS server.  
6. Verified that the website was reachable using the public IP.  



 Learning Outcomes
- Learned how to design and configure a basic cloud network.  
- Understood the difference between public and private subnets.  
- Practiced hosting a simple website on an AWS EC2 instance.  



 Next Steps
- Add a database in the private subnet (RDS).  
- Use a Load Balancer and Auto Scaling for high availability.  
- Automate the setup using Terraform or CloudFormation.  
