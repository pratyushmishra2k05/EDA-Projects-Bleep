# Bank Marketing Campaign Analysis

## 1. Introduction

This project examines the UCI Bank Marketing dataset to understand which customer characteristics and campaign-related factors are associated with term-deposit subscriptions.

## 2. Dataset Overview

The dataset contains 45,211 records and 17 original columns. The target variable, `y`, records whether a customer subscribed to a term deposit.

## 3. Data Preparation

The initial inspection found no missing values reported by Pandas and no exact duplicate rows. Some categorical fields contain the value `unknown`, which is distinct from a missing value and should be considered during interpretation.

The analysis converted the target into a numerical indicator: 1 for a successful subscription and 0 otherwise.

## 4. Key Findings

- There were 5,289 successful subscriptions out of 45,211 records.
- The overall subscription rate was 11.70%.
- Students had an observed subscription rate of 28.68%.
- Retired customers had an observed subscription rate of 22.79%.
- The subscription rate for tertiary education was 15.01%.
- Cellular contacts had a subscription rate of 14.92%, compared with 13.42% for telephone contacts and 4.07% for records with an unknown contact method.
- March had the highest observed monthly subscription rate at 51.99%.
- Successful subscriptions tended to have longer call durations in the visual comparison.

## 5. Interpretation

Subscription rates vary across job groups, education categories, contact methods and months. These are associations in the observed dataset; they do not prove that any single characteristic caused a subscription.

Monthly rates can be influenced by differences in campaign timing, customer composition and sample sizes. High observed rates should therefore be examined alongside the number of records in each group.

Call duration requires particular care. It is measured after a call takes place, so it should not be treated as information available before contacting a customer.

## 6. Recommendations

1. Investigate the needs and preferences of student and retired customer groups.
2. Compare campaign outcomes across contact methods while considering group sizes and costs.
3. Examine monthly campaign performance before deciding when to allocate future resources.
4. Review previous campaign outcomes to identify potentially useful customer segments.
5. Evaluate contact frequency carefully rather than assuming that more calls produce better results.

## 7. Limitations

The analysis is observational and does not establish causation. Some categorical values are recorded as `unknown`. The findings reflect this dataset and may not generalize to other campaigns or time periods.

## 8. Conclusion

The analysis identifies meaningful differences in subscription rates across customer segments and campaign characteristics. These patterns can guide further investigation and help improve future campaign planning.