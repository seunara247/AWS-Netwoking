This project provides a step-by-step guide to setting up an AWS networking environment with *Virtual Private Cloud (VPC), subnets, security groups, and a NAT Gateway*. This setup ensures that private instances can securely access the internet while maintaining proper access control. 

Firstly, we would create a VPC with both public and private subnet across different *Availability Zones (AZ)* for high availability. The *public subnet* will have direct internet access through an *Internet Gateway (IGW)* to access the internet securely. *Security Gropus (SG)* and *Network Access Control Lists (NACLs)* will be implemented for network security. 

**the pictures of the steps will be added in another folder but each step will be linked to its process**

Before starting make sure you have:

- An AWS account with the necessary IAM permission.

- AWS CLI installed and configured.

- Basic knowledge of AWS networking concepts.

**STEPS**

## 1: Create a VPC - VPC1.JPG, VPC2.JPG

## 2: Create subnets, 1 public and 1 private - VPC3.JPG, VPC4.JPG, VPC5.JPG

## 3: Create and Attach an IGW to the VPC - VPC6.JPG, VPC7.JPG

## 4: Configure Route Table: create a public route table, add the route table to IGW and associate the public subnet with Route table  - VPC8.JPG

## 5: Create a NAT Gateway for Private subnet 

## 6: Launch Instances for the private and public subnet - VPC9.JPG, VPC10.JPG, VPC11.JPG

## 7: Create SG - VPC12.JPG, VPC13.JPG, VPC14.JPG

## 8: Create NACLs - VPC15.JPG, VPC16.JPG, VPC17.JPG, VPC18.JPG
 
## 9: Deploy and verify set up
