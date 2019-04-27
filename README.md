# Website
serverless-website----
GithubRepo-->CodePipeline-->S3-->CloudFront

3 Templates
#Run template as nested stacks by:
upload rds.yaml and cognito.yaml to S3 bucket and Ref in parent template

#Cretate branch in GitHub and push to CI/CD through Webhook- Version Control
#Source Files need to be put into this repo
