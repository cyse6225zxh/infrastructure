# infrastructure

This templete is used to deploy a VPC with 3 subnets on AWS via cloudformation

First download and install aws cli from https://aws.amazon.com/cli/

Open comman line, configure your profile with aws configure

Create VPC with the .yml file with parameters, for example aws --profile=dev cloudformation create-stack --stack-name thur-vpc --template-body file://CreatVPC.yml --parameters ParameterKey=EnvironmentName,ParameterValue=MyTestVPC