# Starbucks Promotion Strategy

## Project Description

A randomized experiment was conducted by Starbucks. An advertising promotion was tested to see if it would bring more customers to purchase a specific product priced at $10. Since it costs the company $0.15 to send out each promotion, it would be best to limit that promotion only to those that are most receptive to it. 

The Take Home Assignment is available in the Repository.

The goal of this exercise is to build a model to select the best customers to target, maximizing the two following metrics:

1. Incremental Response Rate (IRR) - depicting how many more customers purchased the product with the promotion, as compared to if they didn't receive the promotion.

2. Net Incremental Revenue (NIR) - depicting how much is made (or lost) by sending out the promotion.

Different approaches are described in Jupyter Notebook to solve this problem.
1. Two Models Approach
2. Single Model with additionnal "Receptive" feature
3. Simple Method

An article has been written on this project [here](https://medium.com/@adlef01/starbucks-promotion-strategy-741f2a591ab) 

## Files

1. training.csv: contains the training data, to train our models.
2. Test.csv: contains test data, to test our models and promotion strategy.
3. Starbucks.ipynb: contains the Starbucks Promotion Strategies.
4. test_results.py: contains functions to evaluate the IRR and NIR values. File is provided by Starbucks.

## Requirements

Anaconda, Imblearn, Statsmodels, Seaborn
