# Amazon Vine
## Overview
Amazon vine is a program that reviews Amazon products; companies pay a small fee and provide the products to Amazon Vine members, who then publish their opinion

### Purpose
This big-data is going to require new techinques to process; Apache Spark is comprised of Map Reduce functions that would allows us to systematically count word instances, categorize reviews, and gain insights on their contents- without fully reading. To avoid having to set up a local linux cluster, we'll upload the contents to AWS, then use a google Collab notebook equiped with PySpark to extract, transform and load the data into a Postgre database. Finally we'll use Pyspark to determine if there is any bias towards Vine program reviews
 
## Analysis
From these reviews, the video games file was used
[Amazon Reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

### Extraction

### Results
Originally it was hypothesised Vine program participants would appear symethetic towards the companies and would in turn cast possitive reviews< br />
#### Vine Program
<img width="444" alt="Screen Shot 2022-07-13 at 10 07 41 PM" src="https://user-images.githubusercontent.com/79609464/178896574-dade0046-faff-4ead-8d74-b5d98afb0383.png">
#### Normal Reviews
<img width="435" alt="Screen Shot 2022-07-13 at 10 07 45 PM" src="https://user-images.githubusercontent.com/79609464/178896593-599cd0f1-2372-4b0c-aecc-a2f55c5b07fc.png">
The reults show the opposite, in that Vine 

## Summary
