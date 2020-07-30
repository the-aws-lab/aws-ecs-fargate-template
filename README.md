# aws-ecs-fargate-template
Use this template to setup ecs fargate on aws using cloudformation

## Licence:
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Usage Instructions:

### Variables

| Parameter            |  Type   | Description            | Default                      | Required |
| -------------------- | ------- | ---------------------- | ---------------------------- | -------- |
| ENV                  | String  | Environment            | stage                        | Y        |
| HostedZoneResource   | string  | Route53 Hosted Zone    | example.com                  | Y        |
| AppName              | string  | Application Name       | theawslab                    | Y        |
| ServiceName          | string  | fargate Service Name   | deafult-service              | Y        |


## Execution Steps:

1. Goto AWS CloudFormation Console.
2. Click on Create stack with new resources
3. Specify Template >> Upload a Template >> Upload file >> Next
4. Give a Stack Name
5. Pass all the parameters
6. Click Next on Configure Stack Options
7. Review and Create Stack

