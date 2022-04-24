# Amazon_Vine_Analysis
## Overview of Project
### Purpose
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Access was given to approximately 50 datasets containing reviews of specific products to select from. Reviews of video DVDs was selected for analyis.

## Results
* **How many Vine reviews and non-Vine reviews were there?**

  49 reviews are Vine reviews (paid).

  <img width="620" alt="Paid Vine Reviews" src="https://user-images.githubusercontent.com/96451672/164919315-9a94bdb9-be2e-4908-8386-6d7176cdb311.png">

  151,400 reviews are non-Vine reviews (unpaid).

  <img width="652" alt="Unpaid non-Vine Reviews" src="https://user-images.githubusercontent.com/96451672/164919427-9b96d724-7c4d-4eb1-938f-3f5f6c736560.png">

* **How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**

  9 reviews are 5 star Vine reviews (paid).
  
  <img width="963" alt="Paid 5 Star Vine Reviews" src="https://user-images.githubusercontent.com/96451672/164928970-895c8d13-284b-4276-9483-fda4fcd3a14c.png">
  
  78,061 reviews are 5 star non-Vine reviews (unpaid).
  
  <img width="1005" alt="Unpaid 5 Star non-Vine Reviews" src="https://user-images.githubusercontent.com/96451672/164930222-5e7f7fa1-821e-4d10-9307-926d486248cf.png">

* **What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**

  18.37 (rounded) percent of Vine reviews (paid) were 5 stars.
  
  <img width="796" alt="Percentage of Paid 5 Star Vine Reviews" src="https://user-images.githubusercontent.com/96451672/164933839-46ee0d9f-4e43-4083-8af5-103351181b6b.png">
  
  51.56 (rounded) percent of non-Vine reviews (unpaid) were 5 stars.
  
  <img width="838" alt="Percentage of Unpaid 5 Star non-Vine Reviews" src="https://user-images.githubusercontent.com/96451672/164933883-3cdcbaa3-6014-43b1-ba41-2c633b595792.png">

## Summary
The question arises with some reviews being paid through money to Amazon and free products to consumers through the Vine program, 'is there bias in Vine reviews?'. Among the video DVD reviews, there are a limited number of Vine reviews with only 49 out of 151,449. Out of the 49 reviews only 9 reviews were 5 stars making only 18.37% of them 5 stars. With the minimal amount of Vine reviews, it's hard to conclusively determine whether there definitively is bias in the reviews however with only 18% being 5 stars it's fair to conclude that the reviews are not biased.

An additional analysis to examine the possible bias in Vine reviews is to analyze the number of total votes against helpful votes for Vine reviews. This would allow determining the number of unhelpful votes by subtracting the helpful votes from the total votes. Then a percentage of unhelpful votes from total votes could be determined. If the percentage of unhelpful votes is low then it would help support the conclusion that the Vine reviews are not biased since they are not perceived as unhelpful overall.

