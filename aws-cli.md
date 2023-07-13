
### AWSCLI Command: aws configure

`aws configure`

Explanation: Configures your AWS CLI with access key, secret access key, default region, and output format. 

### AWSCLI Command: aws s3 ls

`aws s3 ls`

Explanation: Lists all S3 buckets in your AWS account. 

### AWSCLI Command: aws s3 cp

`aws s3 cp file.txt s3://my-bucket/file.txt`

Explanation: Copies a local file to an S3 bucket. 

### AWSCLI Command: aws ec2 run-instances

`aws ec2 run-instances --image-id ami-12345678 --instance-type t2.micro --key-name my-keypair`

Explanation: Launches a new EC2 instance with the specified AMI, instance type, and key pair. 

### AWSCLI Command: aws ec2 describe-instances

`aws ec2 describe-instances`

Explanation: Retrieves information about EC2 instances in your account. 

### AWSCLI Command: aws ec2 start-instances

`aws ec2 start-instances --instance-ids i-12345678`

Explanation: Starts a stopped EC2 instance. 

### AWSCLI Command: aws ec2 stop-instances

`aws ec2 stop-instances --instance-ids i-12345678`

Explanation: Stops a running EC2 instance. 

### AWSCLI Command: aws ec2 terminate-instances

`aws ec2 terminate-instances --instance-ids i-12345678`

Explanation: Terminates an EC2 instance. 

### AWSCLI Command: aws ec2 create-image

`aws ec2 create-image --instance-id i-12345678 --name "My server backup"`

Explanation: Creates an AMI from an EC2 instance. 

### AWSCLI Command: aws rds describe-db-instances

`aws rds describe-db-instances`

Explanation: Retrieves info about RDS database instances. 

### AWSCLI Command: aws rds create-db-instance

`aws rds create-db-instance --db-instance-identifier mydb --engine mysql --master-username admin --master-user-password `mypassword --allocated-storage 20

Explanation: Creates a new RDS database instance. 

### AWSCLI Command: aws rds delete-db-instance

`aws rds delete-db-instance --db-instance-identifier mydb --skip-final-snapshot`

Explanation: Deletes an RDS database instance without a final snapshot. 

### AWSCLI cmd: aws lambda create-function

`aws lambda create-function --function-name my-function --runtime python3.8 --handler my_function.handler --role arn:aws:iam::123456789012:role/my-role --zip-file fileb://function.zip`

Explanation: Creates a new Lambda function 

### AWSCLI Command: aws lambda invoke

`aws lambda invoke --function-name my-function --payload '{"key1":"value1", "key2":"value2"}' response.txt`

Explanation: Invokes a Lambda function synchronously and saves the response. 

### AWSCLI Command: aws lambda update-function-code

`aws lambda update-function-code --function-name my-function --zip-file fileb://function.zip`

Explanation: Updates the code of an existing Lambda function. 

### AWSCLI Command: aws cloudformation create-stack

`aws cloudformation create-stack --stack-name my-stack --template-body file://template.yml`

Explanation: Creates a CloudFormation stack using a template file. 

### AWSCLI Command: aws cloudformation describe-stacks

`aws cloudformation describe-stacks`

Explanation: Retrieves information about CloudFormation stacks in your account. 

### AWSCLI Command: aws cloudformation update-stack

`aws cloudformation update-stack --stack-name my-stack --template-body file://updated-template.yml`

Explanation: Updates a CloudFormation stack with a new template. 

### AWSCLI Command: aws cloudformation delete-stack

`aws cloudformation delete-stack --stack-name my-stack`

Explanation: Deletes a CloudFormation stack. 

### AWSCLI Command: aws apigateway create-rest-api

`aws apigateway create-rest-api --name my-api`

Explanation: Creates a new API Gateway REST API. 

### AWSCLI Command: aws s3 sync

`aws s3 sync local-directory s3://my-bucket/`

Explanation: Syncs the contents of a local directory with an S3 bucket, uploading new or modified files and deleting removed files. 

### AWSCLI Command: aws s3 rm

`aws s3 rm s3://my-bucket/file.txt`

Explanation: Deletes a file from an S3 bucket. 

### AWSCLI Command: aws iam create-user

`aws iam create-user --user-name myuser`

Explanation: Creates a new IAM user. 

### AWSCLI Command: aws iam update-user

`aws iam update-user --user-name myuser --new-user-name newuser`

Explanation: Renames an IAM user. 

### AWSCLI Command: aws iam create-access-key

`aws iam create-access-key --user-name myuser`

Explanation: Creates an access key for an IAM user. 
Time for Bonus 😍
### AWSCLI Command: aws iam update-access-key

`aws iam update-access-key --access-key-id ABCDEFG --status Inactive`

Explanation: Updates the status of an access key to either Active or Inactive.
### AWSCLI Command: aws iam list-users

`aws iam list-users`

Explanation: Lists all IAM users in your AWS account.
### AWSCLI Command: aws iam create-group

`aws iam create-group --group-name my-group`

Explanation: Creates a new IAM group.
### AWSCLI Command: aws iam attach-group-policy

`aws iam attach-group-policy --group-name my-group --policy-arn arn:aws:iam::aws:policy/AmazonS3FullAccess`

Explanation: Attaches an IAM policy to an IAM group.
### AWSCLI Command: aws iam create-role

`aws iam create-role --role-name my-role --assume-role-policy-document file://trust-policy.json`

Explanation: Creates a new IAM role with an associated trust policy.
### AWSCLI Command: aws iam update-assume-role-policy

`aws iam update-assume-role-policy --role-name my-role --policy-document file://updated-trust-policy.json`
