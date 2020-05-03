# AWS Service -->  S3
> + Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance.
> +  This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics.
> + Amazon S3 provides easy-to-use management features so you can organize your data and configure finely-tuned access controls to meet your specific business, organizational, and compliance requirements. 

## BUCKET:
> + Bucket is like a folder .we make folder under that we store file into that .same thing we can make folder inside the bucket .It is on you upto what level you have to go!
> + To upload your data (photos, videos, documents etc.) to Amazon S3, you must first create an S3 bucket in one of the AWS Regions. You can then upload any number of objects to the bucket.

> + In terms of implementation, buckets and objects are resources, and Amazon S3 provides APIs for you to manage them. For example, you can create a bucket and upload objects using the Amazon S3 API. 
> + You can also use the Amazon S3 console to perform these operations. The console uses the Amazon S3 APIs to send requests to Amazon S3.
> + An Amazon S3 bucket name is globally unique, and the namespace is shared by all AWS accounts. 
> + This means that after a bucket is created, the name of that bucket cannot be used by another AWS account in any AWS Region until the bucket is deleted. 

## Firewall
Firewall-Filters the network traffic
Os has firewall
1]**Inbound**-you ctrl incoming traffic\
2]**Outbound**- you ctrl outgoing traffic

*Steps for firewall*\
> + Search for firewall

> + Click on  windows defender firewall security
> + You have inbound and outbound rules
> + click on inbound
In that you give the access to the ports .Now suppose you have a server on the port 80
And if we don’t give access here,then from browser no one could access it
> + On RHS>New rule>click on the port>Next >portname-80>next>Allow the connection>Next>select all>next>demp-80-port>finish

+ AWS has given the cloud’s firewall.They also provided inbound and outbound
So that I will be easy for the user .No need to learn the networking.
It is known as the **“Security Groups”**
+ So traffic first goes here then it goes towards the os

