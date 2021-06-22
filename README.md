# Amazon_Vine_Analysis

## Analysis Overview
The purpose of this analysis is to analyze the Amazon Vine Program and determine if there exist any form of bias towards favorable reviews from Vine members.I used PySpark to perform the ETL process which extracted the dataset, transformed the data and connected to an AWS RDS Instance to load the transformed data into pgAdmin and calculate different metrics. 

## Results

### Calculations for paid vine
<img width="1112" alt="Screen Shot 2021-06-22 at 1 49 45 PM" src="https://user-images.githubusercontent.com/78401776/122974934-d5aae500-d360-11eb-83ed-07d1ad3f9143.png">

### Calculations for unpaid vine
<img width="1130" alt="Screen Shot 2021-06-22 at 1 49 52 PM" src="https://user-images.githubusercontent.com/78401776/122974992-e22f3d80-d360-11eb-87ab-dcc59897f7cb.png">



### 1) How many Vine reviews and non-Vine reviews were there?
 - Vine Reviews
<img width="429" alt="Screen Shot 2021-06-22 at 1 48 54 PM" src="https://user-images.githubusercontent.com/78401776/122975075-f7a46780-d360-11eb-9d9a-9b848c153b20.png">

 - Unpaid Vine
 <img width="452" alt="Screen Shot 2021-06-22 at 1 49 22 PM" src="https://user-images.githubusercontent.com/78401776/122975130-0a1ea100-d361-11eb-985c-2c52f91fe2b0.png">


### 2) How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
 - 5 star review for paid vine 
 <img width="464" alt="Screen Shot 2021-06-22 at 1 49 05 PM" src="https://user-images.githubusercontent.com/78401776/122975559-77cacd00-d361-11eb-97c3-8706325ffd0a.png">

- 5 star review for unpaid vine
<img width="452" alt="Screen Shot 2021-06-22 at 1 49 22 PM" src="https://user-images.githubusercontent.com/78401776/122975621-8add9d00-d361-11eb-8143-4ccd9a19076d.png">


### 3) What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Percentage of paid 5 star reviews
<img width="573" alt="Screen Shot 2021-06-22 at 1 49 13 PM" src="https://user-images.githubusercontent.com/78401776/122976351-3dadfb00-d362-11eb-91c9-6fd7bd787467.png">

- Percentage of unpaid 5 star reviews
<img width="571" alt="Screen Shot 2021-06-22 at 1 49 35 PM" src="https://user-images.githubusercontent.com/78401776/122976414-50c0cb00-d362-11eb-9def-82cb6849e91b.png">


## Summary
36% of reviews in the paid Vine program were 5 star reviews whereas the percentage in the unpaid vine reviews was 47%. This describes there is no positive bais towards reviews in the data set. Further analysis could include a statistical distribution which compromises of (mean, median and mode) of the 5 star rating for paid and unpaid reviews




