# Implementing Role-based Access Control in DynamoDB

The initial goal of the project was to implement Attribute based Access Control in NoSQL Databases like DynamoDB. The database service i.e., authorization based on tags is not provided.

NoSQL Databases: Databases with flexible schemas unlike relational databases.

## DynamoDB

Amazon DynamoDB is a fully managed NOSQL database service with seamless scalability providing fast and predictable performance. DynamoDB also supports
encryption at rest, which reduces the time and effort required to safeguard sensitive data. Creation of database tables in DynamoDB allows to store and retrieve any amount of data and handle any amount of request traffic. It enables the creation of comprehensive backups of tables for long-term storage and archival for regulatory compliance needs. DynamoDB uses JSON for its syntax due to its universality. And it is fast as it runs on the newest solid-state drive (SSD) technology and various additional improvements that ensure low latency at any scale.

![Image]()

## What's Attribute based Access Control?

ABAC is defined as an access control method where access is mediated based on a set of attributes and their associated values, where each attribute represents a particular characteristic of a subject, object, or the environment in which the access request is being made. Based on the combination of these attributes that is the subject, object and the environment the access is granted or denied. ABAC provides support for access control decision making without a prior knowledge of the object by the subject or knowledge of the subject by the object owner. ABAC is implemented to reduce risks due to unauthorized access, as it can control security and access on a more fine-grained basis.

![Image]()

## Implementing bulk CSV ingestion to Amazon DynamoDB:

You can use your own CSV file or download the test file provided in this repo. 

## Steps to Download CloudFormation template:
1. Click on csvtodynamo.template.
2. Click on the Raw button.
3. Save Page As > Remove any file extensions so that the file reads like "csvtodynamo.template". Click save.

## Flowchart for Amazon DynamoDB:

![Image]()

## Output Images:

![Image]()
*Figure: Read-only user unable to edit or make changes*

![Image]()
*Full Admin User able to make changes*
