# Data Engineering - YouTube Analysis Project

## Overview
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

## Project Goals
1. Learn how to build a data lake from scratch using Amazon S3
2. Understand the difference between data lake and data warehouse
3. Design data lake and build a data pipeline around it
4. Utilize AWS services such as SNS and IAM
5. Write SQL queries to analyze data using Amazon Athena
6. Ingest data incrementally and build a proper schema
7. Visualize data using a dashboard

## Services we will be using
1. Amazon S3: When it comes to handling large-scale storage needs while maintaining data availability, security, and performance, Amazon S3 shines. It's the ideal choice for establishing a robust storage foundation.
2. AWS IAM: For secure access management to AWS services and resources, AWS IAM steps up. Use it to control permissions, ensuring data integrity and confidential handling throughout your project.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: Simplify data integration and preparation with AWS Glue. When you need to organize and combine data for analytics, ML, or app development, Glue's serverless approach streamlines the process.
5. AWS Lambda: If you want to automate tasks without worrying about server management, AWS Lambda is the solution. It's perfect for triggering actions based on events, boosting workflow efficiency.
6. AWS Athena: When real-time querying of data without the need for data loading is on the agenda, turn to AWS Athena. It's your tool for direct querying of data residing in Amazon S3, minimizing data movement.

## Dataset Used
The Kaggle dataset provides a comprehensive collection of daily statistics on popular YouTube videos over an extended period of time. Each region has its own file, containing up to 200 trending videos published every day. The data includes information such as video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count. Additionally, a category_id field is included in the JSON file linked to the region, which varies by area. The data is presented in CSV format for easy analysis and manipulation.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">
