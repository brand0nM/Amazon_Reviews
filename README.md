# Spark
## Overview
Samsung has hired us to analyse all the reviews of their new phone, then compare these reviews with their competitors. They are also interested in giving a free product to select reviewiers, but are unsure of the cost benifit payout
### Purpose
Samsungs new phone has 10's of thousands of reviews (Big Data), so we must first translate each review in order to analyse them. Though large scale data is traditionally processed with hadoop, my current hardware configuration is not intended for this purpose. With the advent of cloud computing, Apache Spark has allowed us to set up specific instances of hadoop without reconfiguring a server. Spark is substantially more efficient than hadoop because it uses memory based computation instead of disk based- meaning there is less comunication back and forth between the memory and disk components/Spark uses lazy evaluations.

[Amazon Review Links](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
