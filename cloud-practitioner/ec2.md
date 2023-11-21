# AWS EC2

EC2 is one fo the most popular of AWS's offering. EC2 stands for Elastic Compute Cloud. It mainly consists in the capability of:

* Renting virtual machines (EC2)
* Storing data on virtual drives (EBS)
* Distributing load across machines (ELB)
* Scaling the services using an auto-scaling group (ASG)

Knowing EC2 is fundamental to understand how the Cloud works.

## EC2 Sizing & Configuration Options

* Operating system: Linux or Windows
* How much power & cores (CPU)
* How much RAM
* How much storage space
    * Network-attached (EBS & EFS)
    * hardware (EC2 instance store)
* Network card: speed of the card, public IP address
* Firewall rules: security groups
* Bootstrap script: launch commands on the instance at first start (EC2 user data)

## EC2 Instance Types

There are many different types of EC2 instances, optimized for different use cases. You can find it [here](https://aws.amazon.com/ec2/instance-types/).

