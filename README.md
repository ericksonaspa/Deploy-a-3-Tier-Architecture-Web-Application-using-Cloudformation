# Deploy-a-3-Tier-Architecture-Web-Application-using-Cloudformation

This project is a walkthrough of using Cloudformation in building a 3-tier architecture web application in Amazon Web Services (AWS). We will be creating the layers of the architecture in the following order: 

1. Create a VPC, public and private subnets, public route tables
2. Create 2 NAT gateways, elastic IP addresses, and private route tables
3. Create an RDS MySQL database
4. Create an Application Load Balancer, listeners, target groups and execute user data
5. Create a launch template and auto-scaling group
