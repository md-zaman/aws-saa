1. Data Centre > Availability Zone > Region

2. AWS ensures data is secure by redundancy. We store store content on data 
centres, AWS ensures redundancy by saving it to another DC through redundant 
high speed low latency links. This way if the 1st DC goes down the 2nd one
is up and running. This cluster of DCs are called Availability Zone.

Similarly cluster of AZs make a Region all the AZs in a Region are 
connected by `redundant` `high speed`, `low latency links`.

Which region to choose. There are 4 basic aspect you need to consider 
for this:
    a. Compliance
    b. Latency
    c. Pricing
    d. Service availability

3. Edge Location where data is cached so that you don't have to download 
any content every now and then. It will be stored near your location.



# Stephane Maarek from Udemy

## 3 - Getting Started with AWS

4. Global Services of AWS
    a. IAM
    b. Route53
    c. CloudFront (CDN)
    d. WAF (Web Application Firewall)

5. Most AWS services are Region-Specific:
    a. EC2 (IaaS)
    b. E Beanstalk (PaaS)
    c. Lambda (Func. as a Service)
    d. Rekognition (Softw. as a Service)

9 - Tour of AWS Console Services in AWS

6. You can go to global infrastructure regional product service link to find out which regions have which services.Remember that not all services are available in every region.

# 4 - IAM AWS CLI

## 11 - IAM Introduction Users Groups Policies

7. You should not use the root account and create a user from the root user instead.
8. Users can be added into `Groups`. Groups Only contain user- remember that. A user can belong to multiple group.
9. Users or Groups can be assigned JSON documents called policies.
10. Policies define the permissions of the `Users`.
11. In AWS you apply the `least privilege principle`: don't give more permissions than a user needs.
12. IAM is a Global Service.




