![](https://raw.githubusercontent.com/aws/aws-cdk/master/logo/default-128-dark.png)

# aws-cdk-qcon-workshop

This workshop walks you through building sample serverless and container apps with AWS CDK.



# Prerequisities



## Install and setup npm

```bash
# install the nvm installer
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
# nvm install 
nvm install lts/dubnium
nvm alias default lts/dubnium

```



## Install and setup aws-cdk

```bash
# install AWS CDK
npm i -g aws-cdk
# check cdk version
cdk --version
1.13.1 (build 96cfc63)
```



## Install and Configure AWS CLI

1. Follow this [guide](https://docs.aws.amazon.com/zh_cn/cli/latest/userguide/cli-chap-install.html) to install AWS CLI.
2. Create your own IAM user and run `aws configure` to configure your AWS CLI default profile

3. run `aws sts get-caller-identity` to check the output

```bash
{
    "UserId": "AIDAJVHX3XBRH4E4UGWWK",
    "Account": "112233445566",
    "Arn": "arn:aws:iam::112233445566:user/pahud"
}
```



## Install Docker

Install Docker Desktop for your [Mac](https://docs.docker.com/docker-for-mac/) or [Windows](https://docs.docker.com/docker-for-windows/)



# Go to the Labs

Lab1 - [Build your 1st Serverless Container App with AWS CDK](./Lab1/)

Lab2 - [Build your serverless URL-shortener App with AWS CDK](./Lab2/README.md)

