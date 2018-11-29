# AWS Cloud Native Todo App Deployment Lab

__Status: Under construction. Do not use this content yet.__

This repository contains instructions and resources required to deploy a simple cloud native todo application onto AWS.

## Application Structure

* TODO: Static Vue.js website hosted in S3.
* TODO: Website publishing through AWS CloudFront.
* TODO: Todo list data stored in DynamoDB.
* TODO: Lambda functions for back end API.
* TODO: Back end API published through API Gateway.
* Deployment through Command Line Interface and AWS CloudFormation.

## Setup and Deployment

The steps below will deploy a cloud native Todo application onto Amazon Web Services. They are deliberately written as high level steps to decrease the maintenance overhead of this document. You will need to discover the fields to fill out and buttons to click yourself.

If you discover something wrong with the application or deployment steps, please open an [issue on GitHub](https://github.com/DDLSTraining/lab-aws-todo/issues/new).

To deploy this Todo application follow the steps below.

### Initial AWS Account Setup

This section will create a new AWS account for you to run the example application. It will also configure the AWS Command Line tool with access keys. If you already have an account with CLI access you can skip to the [???](#???) section.

1. Create an [AWS account](https://portal.aws.amazon.com/billing/signup).
1. [Secure the Root User Account](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html) and create a new Admin account.
1. Enable `Programmatic access` for your Admin account by generating an `Access key ID` and a `Secret access key`.
1. Download and install the [AWS Command Line Interface](https://aws.amazon.com/cli/) tool.
1. Open a command line environment (bash, cmd.exe, or PowerShell) and run the following command:
   * `$ aws configure`
1. Type the following values into the console when prompted:
   * AWS Access Key ID
   * AWS Secret Access Key
   * Default region name (`ap-southeast-2` for Sydney)
   * Default output format (leave set to `none`)
1. Test the CLI configuration by running the following command:
   * `$ aws iam list-users`
   * You should see one or more users listed within a JSON document.

You now have an AWS account with the command line interface configured.

### ???


### Todo App Cleanup

1. If you no longer need them, remove your Admin account `Access Key ID` and `Secret Access Key`.