# Discovering-Edibility-Patterns-in-Mushrooms-using-Association-Rule-Mining

## Project Overview

This project analyzes the Mushroom dataset to discover patterns that indicate mushroom edibility using Association Rule Mining. By applying the Apriori algorithm, the project identifies frequent itemsets and generates association rules that help predict whether a mushroom is edible based on its physical characteristics.

## Objectives

1. Preprocess the mushroom dataset to prepare it for association rule mining.  
2. Use the Apriori algorithm to mine frequent itemsets with a minimum support of 0.3.  
3. Generate the top 10 association rules based on confidence and lift with minimum confidence of 0.7.  
4. Interpret and explain a selected association rule from the results.

## Dataset

The Mushroom dataset contains categorical features describing physical characteristics of mushrooms, along with a class label indicating edibility (edible or poisonous). 
Link: https://drive.google.com/file/d/1vpktmUajChDbPNrvTKmQHF7BEyP1QL7Y/view?usp=sharing

## Methodology

- **Data Preprocessing:** Convert categorical features into one-hot encoded format suitable for Apriori.  
- **Frequent Itemset Mining:** Apply Apriori algorithm to find frequent itemsets with support ≥ 0.3.  
- **Rule Generation:** Generate association rules with confidence ≥ 0.7.  
- **Rule Selection:** Identify and analyze the top 10 rules based on confidence and lift.

## Selected Rule Example

One notable rule found is:

```python
{odor=none, cap-shape=bell} → {class=edible}
