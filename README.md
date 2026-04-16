# Aws-vpc-project
Implemented VPC with public and private subnets on AWS Project used in production  

 Overview:  

The architecture is set up inside an Amazon VPC across two availability zones for better reliability. It includes public and private subnets, where the public subnets contain an AWS Application Load Balancer to handle incoming traffic and a NAT Gateway for internet access. The application servers run in the private subnets and are managed by an Auto Scaling Group, which automatically adjusts the number of servers based on demand. The load balancer sends user requests to these servers, and the servers can access the internet securely through the NAT gateway. This setup improves availability, security, and scalability. 

 AWS Project: VPC, Auto Scaling, Bastion Host & Load Balancer Setup 

Reference: https://docs.aws.amazon.com/vpc/latest/userguide/vpc-example-private-subnets-nat.html 

 
 Objective 

To design and deploy a scalable and secure AWS infrastructure using: 

VPC with public & private subnets 
Auto Scaling Group (ASG) 
Bastion Host for secure access 
Application Load Balancer (ALB) 
Python-based web server on EC2 instances 

Final Result 

Successfully deployed scalable architecture 
Load Balancer distributes traffic across instances 
Bastion Host ensures secure access to private instances 
Auto Scaling ensures availability 
