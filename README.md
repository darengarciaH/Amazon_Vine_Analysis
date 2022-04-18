# Amazon_Vine_Analysis
## Overview
The purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members in Amazon's Vine Program. The following analysis consists of an outdoors dataset, which uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.
## Results
* I selected outdoor reviews for this analysis, and most of these were unpaid reviewers.
* There were a total of 39,875 reviews, of which 107 were paid and the rest were unpaid (39,768).
* The percentage of the Vine and Non-Vine reviews that were 5 stars were about 52% each, despite the disparity in each category's share of reviews.
<img width="894" alt="Screen Shot 2022-04-18 at 3 04 56 AM" src="https://user-images.githubusercontent.com/92702922/163778315-2df6c8aa-fe84-4ba7-aa79-fd9e320e5bc7.png">
<img width="653" alt="Screen Shot 2022-04-18 at 3 06 29 AM" src="https://user-images.githubusercontent.com/92702922/163778331-6c445c7d-7b15-4c5c-8b7e-a2efd0eff66f.png">
<img width="604" alt="Screen Shot 2022-04-18 at 3 06 51 AM" src="https://user-images.githubusercontent.com/92702922/163778364-3dce6148-81eb-4926-bd70-e8be014ba5b9.png">

## Summary
There seems to be no indication of positivity bias between Vine and non-Vine reviews. However, the observations for both were very skewed, with only 107 being Vine reviews. This would need to be analyzed further with data that involves a greater share of Vine reviews to fully ascertain that the lack of positivity bias is consistent amongst both groups.
