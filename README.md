# aws-lambda-guardduty
This repository contains source code for the aws-lambda-guardduty function.  This AWS Lambda function translates feeds from AWS GuardDuty findings into a list of malicious IP addresses that are then stored in an S3 bucket. A FortiGate can then consume this list as an external threat feed.
