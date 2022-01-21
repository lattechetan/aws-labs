# aws-labs

# Pre-requisites:

RW/Admin Access to below services

1. IAM 
2. CloudFormation
3. CloudWatch
4. Lambda
5. S3

# Steps to create S3 bucket and launch Cfn stack using template provided in repo
1. [Create 3 S3 buckets](https://docs.aws.amazon.com/quickstarts/latest/s3backup/step-1-create-bucket.html)

`i. yourname-20220120-1010-images`
`ii. yourname-20220120-1010-pdf`
`iii. yourname-20220120-1010-txt`

2. [Create CloudFormation Stack](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/GettingStarted.Walkthrough.html) by passing S3 buckets created in Step-1 for respective parameters and using the [template in repo](https://github.com/lattechetan/aws-labs/blob/main/s3-upload-events-to-trigger-lambda.yml).

3. upload files and test

# Reference ppt
[AWS_Lambda_Session_Lab_v2.pptx](https://docs.google.com/presentation/d/1TvNAVBrAcH3WZ5Hx8xANgTnw0d2S7_Z1/edit?usp=sharing&ouid=106842660619150958702&rtpof=true&sd=true)
