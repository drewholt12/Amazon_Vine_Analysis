# Amazon Vine Analysis

## Analysis Overview
This project analyzes paid reviews written by members of the Vine program and determines if there is bias toward products using the Vine program versus those that do not use the Vine program.  Using PySpark, ETL was performed on a dataset of product types, Tools.  An AWS RDS connection was made to load the data into a PostgreSQL server.  PySpark was then used to determine bias in the dataset toward Vine Member’s reviews.      

## Resources
•	Data Source: Amazon Review Datasets, Tools
•	Software: Google Colab, PostgresSQL 11, PGAdmin 4, Pyspark, VSCode, AWS

## Results
•	Number of reviews for Vine and Non-Vine products:
   Vine_Reviews:
   
  ![Paid_Vine_Reviews](https://user-images.githubusercontent.com/79231355/123695879-b7415f80-d820-11eb-80ae-72a14286a584.png)

   Non_Vine_Reviews:
   
  ![unpaid_reviews](https://user-images.githubusercontent.com/79231355/123695918-c3c5b800-d820-11eb-9aaf-a4b42a1bb53a.png)

•	Number of 5-star reviews for Vine and Non-Vine products:

   5-star Vine reviews:
   
   ![Paid_fivestar](https://user-images.githubusercontent.com/79231355/123695967-d3dd9780-d820-11eb-8855-e81c3f709acf.png)
    
   5-star Non Vine reviews:
   
   ![unpaid_fivestar](https://user-images.githubusercontent.com/79231355/123696007-df30c300-d820-11eb-8e19-1cb63dc70df5.png)

•	Percentage of 5-star reviews for Vine and Non-Vine products:

   Percent 5 star Vine
   
   ![paidfivestar_percent](https://user-images.githubusercontent.com/79231355/123696027-e8ba2b00-d820-11eb-8390-bd9e4001085a.png)
    
   Percent 5 star Non Vine
   
   ![unpaid_fivestar_percent](https://user-images.githubusercontent.com/79231355/123696076-f53e8380-d820-11eb-9e52-fbb82261af18.png)


## Summary
The total number of reviews indicates that Vine related products have fewer reviews for their products than Non Vine related products.  This could be due to the products being new to the market or that Tools generally are not participating in the Vine program.  The overall percentage of 5-star reviews is higher with Vine participating products indicating positive bias.  A better indicator of vias would be analysis of all levels of reviews for both Vine and Non Vine products.  If there is a wider distribution of the reviews with Vine related products, it would indicate increased positive bias with Vine reviews.  
