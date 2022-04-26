# Amazon_Vine_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Musical_Instruments_v1_00.tsv.gz


<img width="612" alt="Captura de Pantalla 2022-04-26 a la(s) 15 50 07" src="https://user-images.githubusercontent.com/84519822/165405081-5f95e5bb-e74b-4d86-accf-e510a6f875e9.png">

<img width="751" alt="Captura de Pantalla 2022-04-26 a la(s) 15 50 23" src="https://user-images.githubusercontent.com/84519822/165405097-6a3f2da6-f1ff-4801-ab80-798d748c194e.png">

<img width="299" alt="Captura de Pantalla 2022-04-26 a la(s) 15 50 38" src="https://user-images.githubusercontent.com/84519822/165405108-091d662d-f84e-452b-ad4a-d155be3a6c76.png">

<img width="701" alt="Captura de Pantalla 2022-04-26 a la(s) 15 50 56" src="https://user-images.githubusercontent.com/84519822/165405121-b0cd3eba-995c-414a-a1a1-de88e4c3a2e8.png">


## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
