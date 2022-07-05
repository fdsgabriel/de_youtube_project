# Data Engineering YouTube project

The main focus here is load, treat and realease a high great data for any analystics one. To do so, I use some trending YouTube statitics from Kaggle (avaiable on this repo). Step by step is: Upload data to AWS S3 at raw bucket; Split different files: CSV to one folder, JSON to another one. Data catalog by AWS Glue, define columns types for example; Transform CSV and JSON (unested data) data using AWS Lambda to Parquet file; Save cleaned data on new bucket ready to be used.

The flow of the process is illustrated on the image attached.