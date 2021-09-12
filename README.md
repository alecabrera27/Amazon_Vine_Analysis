# Amazon_Vine_Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like “SellBy” pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project, we are analyzing Amazon reviews of jewelry products, written by members of the paid Amazon Vine program using  PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin, then use Pandas to determine if there is any bias toward favorable reviews from Vine members in your dataset.
___

## Results

- We have 21 vine members reviews and 7689 reviews from non-vine members 

![Vine_Reviews_Count](https://user-images.githubusercontent.com/78781719/132966833-a82afe9c-5c61-4f8f-940d-0c0c71842b01.PNG)

![non_Vine_Reviews_count](https://user-images.githubusercontent.com/78781719/132966837-5ab487a0-39ca-47d3-a807-091a9ac4ce2a.PNG)

- For the 5 -star reviews we have 11 from Vine members and 4444 from non-Vine members

![5_Star_vine_reviews](https://user-images.githubusercontent.com/78781719/132966870-18a9382e-18cb-4cce-88db-ead1ec9adb4f.PNG)

![5_star_nonvine_reviews](https://user-images.githubusercontent.com/78781719/132966875-bff111f9-313b-4376-b68e-15b03527f164.PNG)

- The percentage of Vine reviews is 52.38%

![percentage_5_star_vine](https://user-images.githubusercontent.com/78781719/132966914-2700be99-7b97-4ea4-9444-e64eea26e25f.PNG)

- The percentage of Non-Vine reviews is 57.79%

![percentage_5_star_nonvine](https://user-images.githubusercontent.com/78781719/132966921-8ce47df6-e4f2-4240-89b4-d56c1fd71c70.PNG)


