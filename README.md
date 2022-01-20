# aws-labs

1. [Create 3 S3 buckets](https://docs.aws.amazon.com/quickstarts/latest/s3backup/step-1-create-bucket.html)
i. <name>-20220120-1010-images
ii. <name>-20220120-1010-pdf
iii. <name>-20220120-1010-txt

2. [Create CloudFormation Stack](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/GettingStarted.Walkthrough.html) by passing S3 buckets created in Step-1 for respective parameters and using the [template in repo](https://github.com/lattechetan/aws-labs/blob/main/s3-upload-events-to-trigger-lambda.yml).

3. upload files and test
