# Amazon Vine Analysis

## Overview of the project 

The purpose of this project was to analyze a big dataset of watch reviews and making use of PySpark, AWS RDS, Pandas and PostgreSQL get insights that could help the company Sellby to improve his service.

## Results

After filtering the table to have only the reviews that have 20 or more votes (which can give us a better view of the service than those reviews with only 1 or 2 votes) and that at least 50% of those reviews are considered helpful, we reduced our dataset from 960.000 reviews to 84.000

The resulting data frame looks like this: 

![df1](https://user-images.githubusercontent.com/81272629/128635458-a80c45ba-540c-464e-8580-c7dea2088ed5.png)

With this data frame we address the following questions:

- How many Vine reviews and non-Vine reviews were there?

There are 47 paid reviews and 8362 unpaid reviews, which means that an overwhelming majority bought and left a product review voluntarily.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

15 of the paid reviews were 5 stars, where 4332 of the unpaid were 5 stars 

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

We found that 32% of paid reviews were 5 stars, while 52% of unpaid reviews were 5 stars, which may mean that people who take a closer look at the product and the service provided by Sellby, tend to to leave a lower rating review.

## Summary

We found that those reviews with 20 or more votes and that at least 50% of those votes are considered helpful, tend to have good reviews with half of the reviews being 5 stars, we also found that the paid reviews have a lower rating that the unpaid reviews. If we perform the analysis again but in this case using 4 stars reviews we see that 16% of the 4 stars are unapaid reviews, while 42% are paid reviews, which may mean that the people in the paid reviews tend to be more demanding when it comes to rate the product with 5 stars

