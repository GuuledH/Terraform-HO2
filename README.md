# Terraform-HO2

Here I have Creating a 2-Tier AWS Architecture With Terraform

The main objectives were:

- Deploy a VPC with CIDR 10.0.0.0/16 with 2 public subnets with CIDR 10.0.1.0/24 and 10.0.2.0/24. Each public subnet should be in a different AZ for high availability.

- Create 2 private subnet with CIDR ‘10.0.3.0/24’ and ‘10.0.4.0/24’ with an RDS MySQL instance (micro) in one of the subnets. Each private subnet should be in a different AZ.

- A load balancer that will direct traffic to the public subnets.

- Deploy 1 EC2 t2.micro instance in each public subnet.

![image](https://user-images.githubusercontent.com/111139456/203401165-32c929f5-2597-4723-89cf-bb514445d610.png)


For Study reference (Two-tier architecture consists of two layers : Client Tier and Database (Data Tier))
