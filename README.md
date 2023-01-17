# Amazon_Vine_Analysis

## Overview
The purpose of this assignment was to review customer reviews for products offered by Amazon. We got to choose from a list of products and I chose Video Games. The data sheet can be found here: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz. The data we analyze will provide us with information regarding the relationship between the Amazon Vine program and 5 star reviews for a given product.
 
 I performed an ETL process on the data once it was imported into google colab. The data was broken down into 4 different dataframes: Review, Customer, Product, and Vine. The data was then imported into a Postgres database that we created through AWS at the start of the challenge and analyzed further. The last step was running the data through a Jupyter Notebook also known as Pandas Python. 

## Results

The total number of reviews was: 40,565
The total number of paid reviews was: 94
The total number of paid five star reviews was: 48
The total number of unpaid reviews was: 40,471
The total number of unpaid five star reviews was: 15,663

The percentage of paid five star reviews to total reviews was: 0.118329

The percentage of  unpaid five star reviews to total reviews was: 38.612104

<img width="1354" alt="Vine_Analysis_Review_Summary" src="https://user-images.githubusercontent.com/111392120/212781217-81943f8e-0b5e-4ef2-9322-0a017ba2e0ff.png">

## Summary
Is there bias: There does not seem to be  bias according to the data. The percentage of paid 5 star reviews is so low that it indicates that there is little to no incenetive for providing a 5 star review. For futher study I would suggest doing the same project for all the reviews and look for a corelation that way. 
