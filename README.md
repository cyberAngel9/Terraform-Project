# Terraform-Project
#In this Project I was able to deploy a webserver in AWS automated with Terraform.  

#1.Created a VPC
#2.Created a Internet Gateway
#3.Created a Custom Route Table
#4.Created a Subnet
#5.Associated The Subnet with a Route Table
#6.Created Security Group to allow ports 22,80,443 (SSH, HTTP, HTTPS)
#7.Created a network interface with an ip in the subnet that was created in step 4
#8.Assigned an elastic IP to the network interfacecreated in step 7
#9.Created ubuntu server and installed/enabled apache2
