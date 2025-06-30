# VPC Module
This module is developed for creating VPC module. project Roboshop follows this module

## Inputs
- project (required) - User should specify their project name 

- environment (required) - User should specify their environment

- public_subnet_cidrs (required) - User should specify subnet CIDR block for public subnet
  
- private_subnet_cidrs (required) - User should specify subnet CIDR block for ptivate subnet

- database_subnet_cidrs (required) - User should specify subnet CIDR block for database subnet

- cidr_block (optional) - User can provide their CIDR block. Default value is 10.0.0.0/16

## Outputs
- vpc_id - Exports VPC ID created

- public_subnet_ids - Exports public subnet ids created

- private_subnet_ids - Exports private subnet ids created

- database_subnet_ids - Exports database subnet ids created
