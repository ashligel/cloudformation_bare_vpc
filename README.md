# cloudformation_bare_vpc
An AWS CloudFormation template to deploy a bare VPC with a single Public Subnet.

## How to run

Issue the command using aws cli:
```
aws cloudformation create-stack --stack-name "MyVPC" --template-body file://vpc_template.yml --parameters file://vpc_parameters.json 
```