# E-Commerce Sales and Customer Behaviour Analysis

## 1. Introduction

This project explores the UCI Online Retail dataset to understand transaction patterns, product performance, customer spending and sales trends.

## 2. Dataset Overview

The original dataset contains 541,909 records and eight columns, including invoice number, product code, description, quantity, invoice date, unit price, customer ID and country.

## 3. Data Preparation

Exact duplicate rows were removed, along with rows without product descriptions. Customer-level analysis excludes records without customer IDs. The completed-sales dataset excludes cancelled invoices, non-positive quantities and non-positive unit prices.

After these steps, 392,692 transaction lines remained in the completed-sales dataset.

## 4. Analysis and Findings

- Total revenue in the completed-sales dataset was £8,887,208.89.
- The analysis contained 18,532 distinct completed invoices and 4,338 customers.
- Average invoice value was £479.56.
- The United Kingdom generated the highest revenue.
- Among countries outside the UK, the Netherlands generated the highest revenue.
- November 2011 was the highest-revenue month among the months shown in the analysis.
- PAPER CRAFT, LITTLE BIRDIE was the highest-revenue product in the analysis.
- Thursday recorded the highest total revenue among weekdays in the dataset.
- The correlation between quantity and line revenue was approximately 0.91.

## 5. Interpretation

Revenue varies across products, countries and months. The strong positive relationship between quantity and line revenue is consistent with larger quantities contributing to higher transaction-line revenue. Product prices and the distribution of purchases also matter.

The observed cancellation rate was calculated from the customer-linked dataset and should be interpreted with that denominator in mind.

## 6. Business Recommendations

1. Monitor high-revenue products and maintain appropriate stock levels.
2. Compare country-level performance to identify opportunities outside the UK.
3. Investigate seasonal revenue changes before making inventory decisions.
4. Review cancellation patterns to identify possible operational issues.
5. Use customer-level purchasing behaviour to develop appropriate retention strategies.

## 7. Limitations

The analysis describes historical transactions and does not establish causal relationships. Revenue reflects the cleaning decisions described in the notebook. Missing customer IDs limit customer-level analysis, and the dataset may not represent current retail behaviour.

## 8. Conclusion

The analysis identifies important differences in revenue across products, countries and time periods. These findings can support further investigation of inventory planning, customer retention and international sales opportunities.