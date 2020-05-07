# Udagram
Creation of a network and server Infrastructure in AWS using CloudFormation scripts (IAAC)
This project involves setting up a Network Infrastructure on AWS using the Infrastructure as a COde approach using Cloudformation. It also involves setting a server Infrastructure.
Deployment of Networking components
VPC
Private Subnet
Public Subnet
Internet Gateway to allow resources to connect to Intenet
NAT Gateway (NAT Gateway EIP + NAT gateway resources)to allow Private Subnet to connect to Internet
Routing rules
a.	Route tables
b.	Default Public route
c.	Route Table association

Deployment of Server components:
Security Group 
a.	Load Balancer
b.	Web Server Security Group
AutoScaling Group
a.	Launch Configuration setup (4 servers, two in each private subnets, managed by AutoScaling Group, two VCPUS, min. 4GB Ram, Ubuntu 18,  
b.	autoscaling Group
Load Balancers
a.	Target Group
b.	Listener Rule
c.	Listener
