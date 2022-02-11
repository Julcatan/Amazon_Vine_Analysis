# Amazon_Vine_Analysis

## Overview of the analysis: 
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, I have analyzed the following dataset containing Jewelery reviews: 

"https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Jewelry_v1_00.tsv.gz"

The goal is to determine if there is any bias toward favorable reviews from Vine members in the dataset. 


## Results: 
        
### How many Vine reviews and non-Vine reviews were there?
    
    The dataset contained:
     - 21 paid (Vine) reviews
     
    
  ![image](https://user-images.githubusercontent.com/91682586/152696895-ce988b46-6883-4b5d-9103-7d12acbf7e70.png)

      - and 7689 unpaid (non-Vine) reviews
    
  ![image](https://user-images.githubusercontent.com/91682586/152696917-537d5053-d5df-44c6-9676-2d47f2534062.png)

    
    
### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - 11 paid reviews received 5 stars.
    
   ![image](https://user-images.githubusercontent.com/91682586/152696949-f72fbcda-85a1-4d70-9559-6bdc2fa5c777.png)

    - 4444 unpaid reviews received 5 stars.
    
   ![image](https://user-images.githubusercontent.com/91682586/152696967-f3b9fed2-0f9a-4c71-9b69-8470b77caa92.png)

   

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

    - 52,4% percent of paid Vine reviews were 5 stars
    
   ![image](https://user-images.githubusercontent.com/91682586/152696788-29700f0e-2906-4932-bc63-22783f66c757.png)

    - 57,9% percent of unpaid Vine reviews were 5 stars
    
  ![image](https://user-images.githubusercontent.com/91682586/152697504-0ccae1d7-c2fb-4639-ac76-9cecdd4e5aff.png)

### Summary: 
       
   - The existing data shows no positivity bias for reviews in the Vine program. The percentage of 5 star ratings for unpaid reviews is actually higher than for paid reviews.
   - The evaluation is a bit difficult because we have only a small data set of paid Vines for Jewelery. Therefore it could be that there is positivity bias if we would be given a bigger sample.    
