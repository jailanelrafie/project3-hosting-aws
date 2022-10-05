# Circle CI Pipeline Process

## Orbs
* Node
* Elastic Beanstalk
* AWS CLI

## Jobs
* Build: build the app (API and frontend) and install dependencies
* Deploy: deploying to AWS services

## Workflows
* Step 1: Circle CI builds the app (API and frontend) and installs the required dependencies for app functionality
* Step 2: Circle CI uses the scripts in the code to zip the backend and frontend files and upload them to Elastic Beanstalk and S3 respectively and uses these along with RDS for the database in order to deploy the app to the web
