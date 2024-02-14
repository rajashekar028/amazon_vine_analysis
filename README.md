# Amazon_Vine_Analysis

## Overview of the analysis

This project has the purpose to analyse the Musical Instruments Reviews, working on [Amazon Review Datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) more especificaly [Musical Instruments](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Musical_Instruments_v1_00.tsv.gz).
In order to have this analysis, a powerful was necessary to process the Big Data. Google Collab to process using PySpark and reading the data, storaging and feeding SQL Postgresql. 
The focus of this analyis has the objective to show the interest party to understand the behavior of Amazon Vine Members. 

## Results

* *Create DataFrame for Voting_Percentage , where Count is greater or igual 50* 

Firstly was necessary to filter and create a dataframe with reviews grater than 20 votes. Then below image shows the helpful rating greater or equal to 50%

![](resources/greater_than_50.png)

* *Create Vine Program DataFrame for reviews*

Helpful reviews filter by Vine members, where 'Y' means paid .  
![](resources/vine_table.png)

* *Create Vine Program DataFrame for reviews that are NOT part of the program*

Helpful reviews filter by Vine members, where 'N' means unpaid .  
![](resources/unpaid_reviews.png)

* *5_Star Reviews*

A total of 8,246 5_Star reviews , 214 Paid Vine Member adn 70,303 non Member. 

![](resources/5_Star_reviews.png)

* *5_Star Percentage*

Vine reviews was reponsable for 56.67% , while non-Vine 56.72%

![](resources/percentage_review.png)

