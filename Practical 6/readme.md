# Assignment on Association Rule Learning

## Problem Statement
This assignment is focused on discovering association rules between items in a retail dataset. The dataset contains transaction records from a retail company over one week, with each record representing a list of items sold in a single transaction. The goal is to identify association rules that help understand item relationships and customer behavior.

## Data Set
You can download the Market Basket Optimization dataset from the following link: [Market Basket Optimization Data Set](https://www.kaggle.com/hemanthkumar05/market-basket-optimization). Note that there is no header in the dataset, and the first row contains the first transaction. Be sure to set `header=None` while loading the dataset.

### a. Follow the Following Steps
In this assignment, follow the steps outlined below:

### b. Data Preprocessing
Perform data preprocessing as necessary to prepare the dataset for association rule learning.

### c. Generate the List of Transactions
Extract and generate a list of transactions from the dataset. Each transaction should represent a list of items sold in one purchase.

### d. Train Apriori Algorithm
Apply the Apriori algorithm to the dataset to discover association rules between items.

### e. Visualize the List of Rules
Visualize the discovered association rules to gain insights into item relationships.

### f. Rule Generation with Hyperparameters
Experiment with hyperparameters, particularly by increasing the minimum confidence value, to generate rules with different levels of confidence and identify how it affects the rule set.

