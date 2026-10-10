# Bank Marketing Campaign Analysis

## Overview
This project explores a bank marketing dataset to examine customer characteristics and their relationship with term-deposit subscriptions.

## Dataset
Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)

## Tools
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Analysis
- Dataset inspection
- Subscription rate and customer segmentation
- Job and education comparisons
- Contact method and monthly campaign patterns
- Call duration and campaign activity
- Correlation analysis

## Initial results
- Records: 45,211
- Successful subscriptions: 5,289
- Overall subscription rate: 11.70%
- Missing values reported by Pandas: 0
- Duplicate rows: 0

## Files
- `bank_marketing_analysis.ipynb`: analysis and visualizations
- `bank-full.csv`: original dataset

## Notes
The analysis identifies associations in the dataset, not causal relationships. The `duration` variable is known after a call and should not be treated as a pre-call targeting feature.