# AWS Cloud

## AWS Regions

* AWS has regions all around the world, names can be us-east-1, eu-west-3... 
* A region is a cluster of data centers. Most AWS services are region-scoped.

## AWS Availability Zones

* Each region has many availability zones (usually 3, min is 2, max is 6). Take Sydney as an example, ap-southeast-2a, ap-southeast-2b, ap-southeast-2c.
* Each availability zone (AZ) is one or more discrete data centers with redundant power, networking and connectivity, housed in separate facilities. 
* They are separate from each other, thus isolated from disasters.
* They are connected with high bandwidth, ultra-low latency networking.

## Tour of the AWS Console

* AWS has global services: IAM, Route53, CloudFront. WAF
* Most AWS services are region-scoped: EC2, S3, RDS, DynamoDB, Redshift, Elasticache, CloudWatch, CloudFormation, ...
