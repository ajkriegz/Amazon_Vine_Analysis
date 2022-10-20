# Amazon_Vine_Analysis

This analysis was performed using AWS, pgAdmin, Google colab notebooks and pyspark, and pandas.

## Overview

This analysis was performed to determine if there is favorable bias among Amazon Vine members who receive products for free in exchange for writing reviews. This analysis used the Digital Video Games dataset.

## Results

Refer to the following images: 

![alt text](https://github.com/ajkriegz/Amazon_Vine_Analysis/blob/main/Resources/vine_results.png "Checking to see if any reviews in the dataset were by Amazon Vine members.")

![alt text](https://github.com/ajkriegz/Amazon_Vine_Analysis/blob/main/Resources/helpful_non_df.png "DataFrame of non-vine reviews.")

* This dataset contained zero vine reviews at all. Thre were 1685 non-vine reviews considered helpful.

* Of the 1685 non-vine reviews, 631 were five-star ratings.

* That means 37% of reviewers gave five-star ratings.

Below is a summary of these statistics for non-vine reviews.

![alt text](https://github.com/ajkriegz/Amazon_Vine_Analysis/blob/main/Resources/nonvine_statistics.png "Statistics for non-vine reviews.")

## Summary

In conclusion, the current Digital Video Games dataset does not show any positivity bias because the Amazon Vine program would seem to exclude this type of product. To find bias, another dataset would have to be used.

Additional analyses include a breakdown of all five ratings or comparison between verified purchases and non-verified purchases.