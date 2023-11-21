# Cloud

## What is Cloud Computing

### Cloud Computing

Cloud computing is the **on-demand** delivery of computer power, database storage, applications, and other IT resources. Through a cloud services platform with pay-as-you-go pricing. You can provision exactly the right typ and size of computing resources you need. You can access as many resources as you need, almost instantly. Simply way to access servers, storage, databases and a set of application services. AWS owns and maintains the network-connected hardware required for these application services, which you provision and use what you need via a web application. 

### The Deployment Models of the Cloud

* Private Cloud: cloud services used by a single organization, not exposed to the public; complete control; security for sensitive applications; meet specific business needs.
* Public Cloud: cloud resources owned and operated by a third-party cloud service provider delivered over the internet; six advantages of cloud computing: reduce trade capital expense (CAPEX) for operational expense (OPEX), benefit from massive economies of scale, stop guessing capacity, increase speed and agility, stop spending mony running and maintaining data centers, go global in minutes
* Hybrid Cloud: keep some servers on premises and extend some capabilities to the cloud; control over sensitive assets in your sensitive assets in your private infrastructure; flexibility and cost-effectiveness of the public cloud.

### Types of Cloud Computing

* Infrastructure as a Service (IaaS): 

## AWS Cloud Overview

### Regions

AWS has regions all around the world, names can be us-east-1, eu-west-3... A region is a cluster of data centers. Most AWS services are region-scoped.

### Availability Zones

Each region has many availability zones (usually 3, min is 2, max is 6). Take Sydney as an example, ap-southeast-2a, ap-southeast-2b, ap-southeast-2c. Each availability zone (AZ) is one or more discrete data centers with redundant power, networking and connectivity, housed in separate facilities. They are separate from each other, thus isolated from disasters. They are connected with high bandwidth, ultra-low latency networking.

## Tour of the AWS Console

AWS has global services: IAM, Route53, CloudFront. WAF... Most AWS services are region-scoped: EC2, S3, RDS, DynamoDB, Redshift, Elasticache, CloudWatch, CloudFormation, ...