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
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

## Dataset Used
The Kaggle dataset provides a comprehensive collection of daily statistics on popular YouTube videos over an extended period of time. Each region has its own file, containing up to 200 trending videos published every day. The data includes information such as video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count. Additionally, a category_id field is included in the JSON file linked to the region, which varies by area. The data is presented in CSV format for easy analysis and manipulation.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">
