## Project

Deploy a High-Availability Web App using CloudFormation

## Purpose

A company is creating a web application that needs to be automatically deployed into matching infrastructure with supporting software.

## Requirements

---

The following technology is used to run this project:

- [AWS CloudFormation](https://aws.amazon.com/cloudformation/)
- [AWS S3](https://aws.amazon.com/s3/)
- [AWS EC2](https://aws.amazon.com/ec2/)
- [AWS IAM](https://aws.amazon.com/iam/)
- [AWS VPC](https://aws.amazon.com/vpc/)
- [AWS Secrets Manager](https://aws.amazon.com/secrets-manager/)

### Project Files

- `create.sh` Shell script file to run CloudFormation create stack commands
- `update.sh` Shell script file to run CloudFormation update stack commands
- `UdagramWebAppDiagram.png` Deployment infrastructure diagram file
- `udagram-infra.yml` CloudFormation infrastructure template YAML file
- `udagram-servers.yml` CloudFormation resources template YAML file
- `udagram-infra-params.json` CloudFormation infrastructure template parameters JSON file
- `udagram-servers-params.json` CloudFormation resources template parameters JSON file
- `.gitignore` Git ignore file
- `README.md` README documentation

### Deployment Diagram

[AWS Deployment Diagram](UdagramWebAppDiagram.png)
