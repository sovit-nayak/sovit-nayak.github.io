---
layout: page
title: Kafka Stock Stream OLTP on AWS
description: boto3, EC2, S3, AWS Glue, AWS Athena , Apache Kafka
img: assets/img/12.jpg
importance: 2
category: Data Engineering
redirect : https://github.com/sovit-nayak/Kafka-Stock-Stream-OLTP-Project-on-AWS
related_publications: False
---

Project Highlights:
Producers and Consumers: Kafka is used to stream stock market data in real-time. Producers publish the data, and consumers process it for immediate use.

Deployment: The system is hosted on an AWS EC2 instance, ensuring scalability and availability.

Data Storage: Processed data is stored in an S3 bucket, acting as a centralized repository.

Data Analysis:
AWS Glue: Crawlers automate schema discovery and cataloging, enabling structured data for queries.
AWS Athena: Performs SQL-based data analysis directly on the S3 bucket, allowing insights into stock trends and performance.

