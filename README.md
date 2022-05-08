# EC2-with-ruby-cloudformation

To make deploying a Ruby on Rails project as easy as possible as fast with creating a secure environment, this project chose Amazon CloudFormation to document a Ruby on Rails stack from start to finish.

We are creating following resources : 
1. VPC
2. Internet Gateway 
3. Subnets ( Prublic and Private ) 
4. Route table for Subnets
5. NAT Gateway for private Subnet
6. EC2 with Ruby installationa using RVM and Cloudformation Init ( ubuntu 20.04 instance )

There may be issues deploying a particular Rails project using this template, so please fork the project, create changes.

This template is completely free to use, however, Amazon may charge for the use of resources created with it. This template uses the following cost-related services: EC2 and data transfer
