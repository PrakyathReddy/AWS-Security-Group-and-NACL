# AWS Security Group and NACL

VPC + load balancer + internet gateway

Subnet - range of IP address
Each VPC will have one or more subnet / range of IP's
Security at subnet level - using NACL
Security at EC2 level - using Security Groups (SGs)
 
SGs and NACLs act as the last point of security in the AWS a/c

All outbound traffic is by default allowed.
All inbound traffic is denied by default. 

Network Access Control List (NACL) - applied at subnet level. Can Deny or Allow traffic.
SG - can only allow traffic, can't deny

Here's a diagram with both the components involved: 

![AWS Security Group and NACL Overview](overview.png)

