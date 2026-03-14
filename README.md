The purpose of this project was to create a serverless data pipeline using AWS services: Lambda, S3, DynamoDB, in order to ingest, process and export attendance data. Below is the simplifed process.
1. CSV attendance files are uploaded to S3.
2. First Lambda parses CSV and stores records in DynamoDB
3. Second Lambda builds aggregated attendance summaries
4. Third Lambda exports structured summary data to S3.
