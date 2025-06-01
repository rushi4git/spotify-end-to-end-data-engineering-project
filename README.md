# Spotify End-To-End-Data-Engineering Project

### Introduction
In this project, we will build an ETL (Extract, Transform, Load) pipeline using the Spotify API and AWS. The pipeline will retrieve data from the Spotify API, transform it to a desired format, and load it into an AWS data store for further analysis or reporting. 

### Architecture
![Architecture Diagram.](https://github.com/rushi4git/spotify-end-to-end-data-engineering-project/blob/main/spotify_architecture_diagram.jpeg)

### About Dataset/API
This API contains information about music artists, albums and songs.

### Services Used
1. **S3 (Simple Storage Service):** Amazon S3 (Simple Storage Service) is a highly scalable object storage service that can store and retrieve any amount of data from anywhere on the web. It is commonly used to store and distribute large media files, data backups, and static website files.

2. **AWS Lambda:** AWS Lambda is a serverless computing service that lets you run your code without managing servers. You can use Lambda to run code in response to events like changes in S3, DynamoDB, or other AWS services.

3. **Cloud Watch:** Amazon CloudWatch is a monitoring service for AWS resources and the applications you run on them. You can use CloudWatch to collect and track metrics, collect and monitor log files, and set alarms.
