# AWS-IAM
![IAM](https://user-images.githubusercontent.com/19390842/162993316-45bb3fcb-77b8-45b4-9ef3-c90916ca1e5c.PNG)

On this project, we have an average of 100 people on the IT team to move to AWS.
Your role, as a Cloud Specialist, will be to create a migration solution in an automated way.
In addition to migrating these users, it will be necessary to associate permissions to groups and users will must have the MFA (Multi-factor authentication) enabled, adding an additional layer for the security.

Code To Run

1) Open the AWS Cloud Shell

2) Install dos2unix on AWS Cloud Shell (required by the script)

sudo yum install dos2unix -y

3) Download the aws-iam-create-user.sh script on AWS Cloud Shell

wget https://tcb-bootcamps.s3.amazonaws.com/bootcamp-aws/en/aws-iam-create-user.sh

4) Give the proper permission to aws-iam-create-user.sh script

chmod +x aws-iam-create-user.sh

5) Upload the users2.csv file to AWS Cloud Shell

6) Run the script aws-iam-create-user.sh to create the IAM users

./aws-iam-create-user.sh users2.csv
