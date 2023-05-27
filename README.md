# kafka-project

For this project; 
1. EXTRACTION- Extraction was done Python . Code was deployed on AWS Lambda Function and 
   triggered  using Cloudwatch through AWS . 
2. TRANSFORMATION - Apache Kafka hosted on EC2 was utlized to handle real time data streaming. Pandas was also used to perform minor wrangling of data 
   sets. Data sets were streamed from Kafka using its Python Producer and 
   Consumer API and loaded onto S3 in JSON format. 
3. LOADING - AWS Glue Crawler and Data Catalog was used to infer data schema 
   from S3 . AWS Athena is then used to Query datasets. 
