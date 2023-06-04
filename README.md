# Overview

Project is currently in progress.
Project aims to create a fully automated data pipeline that extracts data from Spotify API, transforms it, and stores it in S3, enabling efficient analytics through Glue and Athena.

# Project Steps

1. Integrating with Spotify API and extracting Data
2. Deploying code on AWS Lambda for Data Extraction
3. Adding trigger to run the extraction automatically
4. Writing transformation function
5. Building automated trigger on transformation function
6. Store files on S3 properly
7. Building Analytics Tables on data files using Glue and Athena

# Services we will be using

1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS Lambda is a serverless that lets you run code for different applications or backend services without needing to set up or manage servers.
4. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
5. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.
7. Diagrams.net free online diagram software for making flowcharts

# Spotify API

https://developer.spotify.com/
playlist_link = "https://open.spotify.com/playlist/37i9dQZEVXbMwW10JmAnzE"
