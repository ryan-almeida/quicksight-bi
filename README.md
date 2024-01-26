# Build Dashboards with Amazon QuickSight 

## Analyze and visualize flight data using Amazon QuickSight and practice using Business Intelligence (BI) Tools on the cloud to gain insights about your data.

This project is an example that was built alongside the tutorials offered from AWS Skill Builders (www.aosnote.com) that teaches you how to use a BI Tool such as Amazon Quicksight to ingest and prepare data, create visualizations, add filters, create dashboards, and ultimatly gain insight. This project allows you to appreciate the strength of using a pre-built dashbaord tool, such as:

1. Repeatability, and the ability to provision pre-configured environments, offering consistency
2. Decreasing Risk due to human error which may lead to uneccessary troubleshooting and debugging
3. Increasing Security and Faster Recovery in the event of an unecpected attack
4. Faster deployment and execution due to pre-configured enviroments
5. Greater control and situational awareness due to deployments from pre-configured environments
6. Financial savings due to ability to deploy and destroy resources on demand 

In particular, this project will be deplyoed by completing the following steps:

- Terraform overview and setup instructions
- Setting up remote backend in AWS using S3 bucket
- [Optional] Setting up a GitHup profile and repository, installing Git, Visual Studio Code, and AWS CLI to ease access, management and deployment of code
- Writing Terraform syntax to create resources in AWS, which include:
  - Understanding the basic syntax of Terraform init, plan, apply and destroy
  - Creating variables and inputs which enable Terraform configurations to be flexible and composable
  - Creating a VPC (including public/private subnets in multiple Availability Zones)
  - Creating NAT Gateways
  - Creating Security Groups
  - Creating an RDS Instance
  - Creating an EC2 Instance
  - Creating Application Load Balancers and Auto Scaling Groups
  - Creating record sets in Route 53 and AWS Certificate Manager to customize DNS route and secure the website 
- Destroying resources and cleaning up the enviroment
