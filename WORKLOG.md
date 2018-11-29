# AWS Todo App Worklog

* Ensure [AWS CloudFormation Best Practises](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/best-practices.html) are being followed.

* Script the following commands:

```sh

$ aws cloudformation create-stack --stack-name todo-app-s3 --template-body file://./template.json --parameters ParameterKey=???,ParameterValue=???
$ aws cloudformation delete-stack --stack-name todo-app-s3

```