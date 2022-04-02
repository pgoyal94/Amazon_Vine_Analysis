# Amazon Vine Analysis
Analyze Amazon reviews written by members of the paid Amazon Vine program.

## Overview of the analysis: 
We are helping a company that is about to release a large amount of products to a website. They want to know how the reviews of their products compare to the reviews of similar products sold by their competitors. They are also interested in enrolling in a program that gives out free products to select reviewers, but want to know if it is worth it.

## Results: 
Using the Amazon Music reviews file, we have found the following:

_Note:
- Paid = Vine review
- Unpaid = non-Vine review_

How many Vine reviews and non-Vine reviews were there?
- Vine: 7
- non-Vine: 105979

![image](https://user-images.githubusercontent.com/92613639/161379282-63cfb679-7df8-443a-b184-8c6f3b1c06ca.png)

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Vine: 0
- non-Vine: 67580

![image](https://user-images.githubusercontent.com/92613639/161379635-c5292309-121f-456a-a656-7e2c5f617f39.png)

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Vine: 0.00%
- non-Vine: 63.77%

![image](https://user-images.githubusercontent.com/92613639/161379400-b27ee889-d16b-478a-b772-019063a8ad7b.png)

## Summary: 
Looking at the Music reviews data file, it is impossible to provide any results with certainty. There are only 7 vine reviews remaining after cleaning and filtering the data. We show that none of them were 5 star reviews. Seven reviews in my mind is far too few to create a concrete conclusion off of. In order to make this possible, it might be worthwhile looking at data and reviews on other retail sites that are better known for selling their music and see if any of them have a similar program to which we could compare.

If music is not one of the products the company is looking to sell, we may want to redo the analysis on a dataset that more aligns with the types of products we are looking to sell. It may be worth also looking into data surrounding repeat buyers and subscriptions that would allow for a more steady stream of capital flow for the company.
