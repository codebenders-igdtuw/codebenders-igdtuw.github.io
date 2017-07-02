---
layout: post
title: "AWS – Amazon WOW Services"
description: Take a dive in the sea of Amazon Web Services.
category: AWS
headline: Amazon Web Services
tags: [AWS, Cloud Services]
comments: false
mathjax: true
---
Okay yes I know, that is not the most inspired heading for a blog post. But what else can you say about something that quite literally makes you go “WOW”. 

We have all been witness to Amazon’s customer friendly outlook. Their management, customer support, accountability and receptiveness to feedback and criticism are the major pillars that are holding this company at the apex. Now, the people at Amazon have recognized the major contributors to their overall welfare and well being, and are also cashing in on them. How, you wonder? 
Through **Amazon Web Services**.

<figure>
	<a href="{{ site.url }}/images/gallery1/AWS1.png"><img src="{{ site.url }}/images/gallery1/AWS1.png"></a>
</figure>

In the era of virtualization and cloud computing, Amazon Web Services provides holistic support for a complete computing system in cloud. From **infrastructure** to **storage and analytics**, it meets exhaustible needs and requirements of a company, at **optimal price**. Small scale companies can benefit as much as large scale companies owing to their **pay-as-you-use model**. 

<figure>
	<a href="{{ site.url }}/images/gallery1/AWS2.png"><img src="{{ site.url }}/images/gallery1/AWS2.png"></a>
</figure>

This post is going to focus on three of their services, namely **Amazon EC2**, **Amazon S3** and **Amazon Redshift**.



<h2>
<u>
<b>
Amazon EC2
</b>
</u>
</h2>

With the increasing unpredictable workload, it is not wise to use a fixed amount of storage, network, memory space etc. Organizations these days sometimes need to resize their capacity within a limited time period (sometimes even minutes!). Amazon Elastic Cloud Compute (EC2) provides the users with this resizable compute capacity in the cloud through a virtual computing environment, called instance. 

<figure>
	<a href="{{ site.url }}/images/gallery1/AWS3.png"><img src="{{ site.url }}/images/gallery1/AWS3.png"></a>
</figure>

An instance can alternatively be defined as a template that can be reconfigured and set up according to the needs of the user. Different instances can have different configurations of CPU, memory storage and networking capacities. It also provides instance store volumes which can be used to store the temporary data that is deleted when you stop or terminate your instance. These instances are safe to use by virtue of the firewall that enables one to specify the protocols, ports and source IP ranges that define the security groups. The security groups determine what can communicate with your instance. Dynamic cloud computing is facilitated by Elastic IP Addresses that are reserved for use and disappear when the instance server is terminated. To further ease the accommodation of varying amount of work, EC2 provides the feature of auto-scaling, which lets you define metrics to automatically increase or decrease the the number of running instances within minutes.

Before the era of AWS EC2, small developers did not have the investment capital for large scale computing resources to ensure they could handle unexpected spikes in the load. Now, they are free to develop without worrying about the overbearing expenses and resources. 

A major advantage of EC2 (and AWS in general) is the pay-as-you-use approach that they have adopted. The different ways in which you can pay for an EC2 instance are outlined as below - 

-**On Demand Instances -** Pay for the compute capacity by the hour without any upfront payments or commitments. One has the flexibility to increase or decrease the capacity depending on the application that is running, and only pay the specified hourly rate for the instances that are launched.

-**Reserved Instances -** These provide a significant discount as compared to On Demand instances. Under this scheme, one can purchase instances that are always available for a period of one-three years. 

-**Scheduled Instances -** Allows users to purchase instances that are always available on a specified recurring schedule for a period of one year. 

-**Spot Instances -** This scheme allows you to bid on spare EC2 instances, which run your application as long as your bid is above the spot price. They are available at a significant discount as compared to On Demand instances and significantly reduce the cost of running your applications. 

-**Dedicated Hosts -** This is a physical EC2 server dedicated for one’s use. 

For more information on how to launch your own Amazon EC2 instance, please follow the below mentioned link-
 
[https://www.youtube.com/watch?v=OLfmqcYnhUM](https://www.youtube.com/watch?v=OLfmqcYnhUM)



<h2>
<u>
<b>
Amazon S3
</b>
</u>
</h2>

<figure>
	<a href="{{ site.url }}/images/gallery1/AWS4.png"><img src="{{ site.url }}/images/gallery1/AWS4.png"></a>
</figure>

With the increasing volume of data in today’s day and age, the conventional storage methods aren’t enough. The need of the hour is to migrate storage to the cloud, along with other computing resources. Amazon provides the Amazon Simple Storage Service (S3) which can be used to store large amounts of data.
 
S3 fundamentally stores data as objects within structures called ‘buckets’ and has a simple web interface to store and retrieve any amount of data from anywhere on the web. There is no restriction on the amount of data that can be stored in a bucket, with each object being a maximum of 5 terabytes in size. Access to these buckets can be controlled by clearly defining who has the rights to create, update or delete a particular bucket; access logs for the buckets can be viewed and you can choose the region where a bucket should be stored so as to minimise latency and access time. S3 is easy to use, durable, scalable, and secure. It allows users to adopt a data driven approach for storage optimization and efficiency. 

S3 pricing is in accordance with the pay-as-you-use model. The types of storage can be divided into three major categories - 

<figure>
	<a href="{{ site.url }}/images/gallery1/AWS5.png"><img src="{{ site.url }}/images/gallery1/AWS5.png"></a>
</figure>

-**Standard Storage (General Purpose) -** Offers high availability and performance object storage for frequently accessed data. This type of storage is perfect for a wide spectrum of use cases such as cloud applications, dynamic websites, mobile and gaming applications, and big data analytics. 

-**Standard -** Infrequent Access Storage (Infrequent Access) - It is an S3 storage class for data that is access infrequently. It offers high durability and throughput, and low latency. The combination of high performance and low cost makes it ideal for long term storage, backup, and as a data store for disaster recovery. 

-**Glacier Storage (Archive) -** It is a secure, durable and low-cost storage service for data archiving. 

<figure>
	<a href="{{ site.url }}/images/gallery1/AWS6.png"><img src="{{ site.url }}/images/gallery1/AWS6.png"></a>
</figure>

For more information on how to create S3 buckets and use them, follow this link- 

[https://www.youtube.com/watch?v=Yyraql9A_Rc](https://www.youtube.com/watch?v=Yyraql9A_Rc).



<h2>
<u>
<b>
Amazon Redshift
</b>
</u>
</h2>

We discussed the different ways of storing data in the last section. But why is data storage important? Why is it necessary to keep a record of all the data and information that has been used by an organization?

<figure>
	<a href="{{ site.url }}/images/gallery1/AWS7.png"><img src="{{ site.url }}/images/gallery1/AWS7.png"></a>
</figure>

The answer is analysis. It is important to analyse and study this stored data so as to identify patterns and correlations between the data in order to help the firm take better business decisions. 

Amazon provides Redshift as a data warehousing service that makes it easier for users to analyse their data using standard SQL and existing business intelligence tools. It is a fast, fully-managed data warehouse that allows users to run complex analytical queries against petabytes of unstructured (unordered, unclassified) data; it uses sophisticated query optimization, and columnar storage. Queries are distributed and parallelized across multiple physical resources, thereby making it more scalable. It proves to be much less expensive than traditional warehousing services as it doesn’t involve any upfront payments or commitments. One can start small with just $0.25 per hour and scale out to petabytes of data for just $1000. Traditional data warehousing methods require constant vigilance and monitoring as the volume of data increases in order to decide the most optimum trade-off between what to store and what to archive. 

Redshift On Demand pricing has no upfront costs. The hourly rate that users have to pay depends on the type and number of nodes in the computing cluster. However, by committing to use Redshift for a term of 1 to 3 years, one can save 75% on On Demand costs . There are two types of storage nodes that are used in Redshift - **Dense Storage** and **Dense Compute**. 

-Dense Storage nodes allow one to create large data warehouses using hard disk drives.

-Dense Compute nodes allow one to create high performance data warehouses using solid state disks.

<figure>
	<a href="{{ site.url }}/images/gallery1/AWS8.png"><img src="{{ site.url }}/images/gallery1/AWS8.png"></a>
</figure>

Click on the below mentioned link for more information on Amazon Redshift- 

[https://www.youtube.com/watch?v=AUvn49gey8Y](https://www.youtube.com/watch?v=AUvn49gey8Y)

This post covered only a drop in the sea of Amazon Web Services. AWS is extensive and covers almost all aspects of cloud computing at an optimal price. We hope to cover more on the same in the upcoming posts!
