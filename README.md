# Amazon_Vine_Analysis

## Overview
The purpose of this project is to see if there's a difference in the percentage of 5-star reviews for video games using Google Colab Notebook, pyspark, and reviews from Amazon S3 databases.

## Results
**How many Vine and Non-Vine reviews were 5 stars?**
There were a total of 20,605 Non-Vine 5-star reviews. There were a total of 65 Vine 5-star reviews.

**How many total Vine and Non-Vine reviews were there in total?
There were a total of 37,790 Non-Vine reviews. There were a total of 170 Vine reviews.

**What percentage of the reviews for both Vine and Non-Vine had 5-star reviews?**
Non-Vine reviews had (20,605/37,790)*100 = 54.53% 5-star reviews. Vine reviews had (65/170)*100 = 38.23% 5-star reviews.

## Summary
The question is, was there any bias and I think the answer is no. Based on the analysis there doesn't seem to be since the Vine reviews have lower 5-star reviews than Non-Vine. I would recommend looking at every review instead of just the 5-star ones to see if the average goes up at all.
