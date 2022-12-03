# Amazon_Vine_Analysis

## Project Overview:
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.

The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.

### Project Challenge:
*SellBy would like to analzye Amazon reviews written by memebers of the Amazon Vine program.*

*The steps involved to perform the analysis will consist of using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.*

*Once the data has been transformed and loaded, the next step is to use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.*

### Deliverables:
- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis (README.md)

### Resources:
- Data Sources:
  - [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
 
- Software:
  - PostgresSQL
  - pgAdmin 4
  - AWS
  - Google Collab

## Project Results:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions:
  - How many Vine reviews and non-Vine reviews were there?
  - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

### Total Reviews:
  - There were a total of 94 Vine reviews.

![1](https://user-images.githubusercontent.com/36451701/128567224-5d1f8262-d411-4b34-b5bc-982bcc0a68b5.png)

  - There were a total of 40,471 non-Vine reviews. 

![4](https://user-images.githubusercontent.com/36451701/128567258-0479b97e-b390-49e0-93c4-ac1d9a1aa90c.png)

### Total 5-Star Reviews:
  - There were a total of 48 Vine 5-star reviews.

![2](https://user-images.githubusercontent.com/36451701/128567245-db73b1ed-3fe2-4ac3-a410-f99057685ec7.png)

- There were a total of 15,663 non-Vine 5-star reviews.

![5](https://user-images.githubusercontent.com/36451701/128567268-2eaaae4d-7213-476f-96f8-a8b8ef6af94d.png)

### Percentage of 5-Star Reviews:
  - 51% of the Vine reviews were 5-star. 

![3](https://user-images.githubusercontent.com/36451701/128567253-b2d5d841-c6ea-4679-8d6f-42065d7660da.png)

   - 38% of the non-Vine reviews were 5-star.

![6](https://user-images.githubusercontent.com/36451701/128567278-12bbcefc-a1f1-49dd-98a1-5fdb4bad1c1a.png)


## Project Summary:
Looking at the percentage of 5-star reviews, there appears to be a positivity bias for the reviews in the Vine program (51%) vs non-Vine reviews (38).

Since we are comparing 94 data points to 40,471, another possible analysis could be looking at summary statistics of the Vine members vs non-Vine participants. 


