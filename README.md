# Amazon_Vine_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

The task is to analyze Amazon reviews written by members of the paid Amazon Vine program. SellBy a company in this Amazon program pays a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this projects we are focusing in musical instruments reviews. The task will be done using PySpark to perform the ETL process, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Afterwards we will look for any positivity bias or negativity in the data set. 

Before showing the results you can see here the demanded data sets for this projects uploaded in pgAdmin. You will also see the pySpark session working properly in the **Google Colab**.

**Review ID DF**
<img width="612" alt="Captura de Pantalla 2022-04-26 a la(s) 15 50 07" src="https://user-images.githubusercontent.com/84519822/165405081-5f95e5bb-e74b-4d86-accf-e510a6f875e9.png">

**Customer ID DF**
<img width="751" alt="Captura de Pantalla 2022-04-26 a la(s) 15 50 23" src="https://user-images.githubusercontent.com/84519822/165405097-6a3f2da6-f1ff-4801-ab80-798d748c194e.png">

**Product ID DF**
<img width="299" alt="Captura de Pantalla 2022-04-26 a la(s) 15 50 38" src="https://user-images.githubusercontent.com/84519822/165405108-091d662d-f84e-452b-ad4a-d155be3a6c76.png">

**Vine Program**
<img width="701" alt="Captura de Pantalla 2022-04-26 a la(s) 15 50 56" src="https://user-images.githubusercontent.com/84519822/165405121-b0cd3eba-995c-414a-a1a1-de88e4c3a2e8.png">


## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?

**Total Vine Reviews:** 60
**Total non-Vine Reviews:** 14,477

*To see the results of this question and the follwing in the code [click here](https://github.com/Rauloigs/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)*

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

**Total Vine Reviews w/ 5 Starts:** 34
**Total non-Vine Reviews w/ 5 Starts:** 8,212

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

**% Vine Reviews w/ 5 Starts:** 56.66
**% non-Vine Reviews w/ 5 Starts:** 56.72


## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
