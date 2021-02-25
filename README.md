# pan-aws-cf
A Cloud Formation templates for Palo Alto Networks firewall in AWS.

## Purpose of the Templates
The purpose is of this template is to build an AWS VPC with Web resources protected by a Palo Alto Networks firewall instance.
The templates include the creation of the following components without any need for you to create them  manualy in the AWS console:
- VPC
- Internet Gateway
- Security Group
- Network ACL
- Subnets
- Routing tables &  Static Routes
- Elastic IP
- Elastic Network interfaces
- PAN Firewall instance
- Web Servers

## Why Should I use this templates ?
Because it will build a full toplogy with all the components above automatically in about 10~15 min.
The template also makes sure there is no inconsistencies and you will be able to test the result very quickly.

## What do I need 
You will need the following before you get started:
- An AWS account
- A PUBLIC S3 bucket where you will setup the following file ( provided in this repository )
-- config/bootstrap.xml
-- config/init-cfg.txt
- The AMI for the Palo Alto Firewall & the Web Server Image ( You can get those in the AWS Market Place )


