# Amazon_Vine_Analysis
---
## Overview of Analysis

We have been tasked with analyzing the Amazon reviews written by members in the paid Amazon Vine Program. I chose to focus on the video game reviews.

### Purpose

The purpose of this analysis was to use PySpark and preform the ETL process on the chosen review data. Additionally, I used PySpark to determine if there is bias toward 5 star reviews with Vine members.

## Analysis

Both Notebooks used to generate the analysis can be found below:

[Amazon_Reviews_ETL.ipynb](https://github.com/ClaudAMC/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb)

[Vine_Review_Analysis.ipynb](https://github.com/ClaudAMC/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)

## Results

1. How many Vine reviews and non-Vine reviews were there?

    The images below show the number of Vine and non-Vine reviews, respectively.

    Vine Members

    ![Total Vine Reviews.PNG](https://github.com/ClaudAMC/Amazon_Vine_Analysis/blob/main/Images/Total%20Vine%20Reviews.PNG)

    Non-Vine Members

    ![Total Non-Vine Reviews.PNG](https://github.com/ClaudAMC/Amazon_Vine_Analysis/blob/main/Images/Total%20Non-Vine%20Reviews.PNG)

    As we can see from the images above there are far more non-vine member reviews (40471) compared to vine member reviews (94).
  
2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    
    The images below show the number of 5 star Vine and 5 star non-Vine reviews, respectively.
    
    5-Star Vine Review
    
    ![Total 5 Star Vine Reviews.PNG](https://github.com/ClaudAMC/Amazon_Vine_Analysis/blob/main/Images/Total%205%20Star%20Vine%20Reviews.PNG)
    
    5-Star Non-Vine Review
    
    ![Total 5 Star Non-Vine Reviews.PNG](https://github.com/ClaudAMC/Amazon_Vine_Analysis/blob/main/Images/Total%205%20Star%20Non-Vine%20Reviews.PNG)
    
    As we can see from the images above there are far more 5-Star non-vine member reviews (15663) compared to vine member reviews (48). However, it is hard to make any assumptions from this as we would need to compare them as a ratio or percentage and not to each other as raw values. This analysis was completed and shown below.
   
3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

    The images below show the percentage Vine reviews and non-Vine reviews that were 5 star, respectively.
    
    Percent 5-Star Vine Review
    
    ![Percent 5 Star Vine to Total Vine Reviews.PNG](https://github.com/ClaudAMC/Amazon_Vine_Analysis/blob/main/Images/Percent%205%20Star%20Vine%20to%20Total%20Vine%20Reviews.PNG)
    
    Percent 5-Star Non-Vine Review
    
    ![Percent 5 Star Non-Vine to Total Non-Vine Reviews.PNG](https://github.com/ClaudAMC/Amazon_Vine_Analysis/blob/main/Images/Percent%205%20Star%20Non-Vine%20to%20Total%20Non-Vine%20Reviews.PNG)
    
    As we can see from the images above 51% of the Vine reviews were 5 Stars. This can be compared to the 39% of Non-Vine reviews that were 5 Stars.
    
## Summary

From the results above we can see that there is a positivity bias for reviews in the Vine program. We can see that there are 12% more 5 star reviews for the Vine reviews compared to the Non-Vine reviews. This suggests that those who are in the Vine program and are getting paid to provide reviews will tend to leave more positive reviews. We could also take a look at the negative reviews or 0 star reviews; this can also show whether Vine revewers were more likely to positively review a product even if the though it deserved a low score - they may leave a 1 or 2 star review as opposed to the 0 star review they may have otherwise given if they were not par of the program.   
    
    
