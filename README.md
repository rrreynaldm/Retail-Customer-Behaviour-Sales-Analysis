# Customer Shopping Data Analysis

## Project Overview

This project analyses customer shopping data to understand purchasing behaviour, product performance, customer demographics, payment preferences, and monthly sales trends. The objective was to identify patterns that could support more effective marketing strategies and help improve sales performance.

The analysis followed an end-to-end process, starting with data cleaning and validation before moving into exploratory data analysis and business recommendations.

## Business Objectives

* Understand customer purchasing and spending behaviour
* Identify high- and low-performing product categories
* Examine the relationship between age, gender, and spending
* Compare customer spending across different age groups
* Analyse customer payment method preferences
* Identify monthly and yearly sales trends
* Develop recommendations for targeted marketing campaigns

## Data Cleaning & Preparation

The dataset required several cleaning steps before analysis:

* Reviewed and corrected inconsistent date formats, removing incorrectly formatted records where appropriate
* Checked for duplicate transactions based on invoice and customer identifiers
* Identified and cleaned missing values
* Standardised inconsistent payment method entries
* Filled missing product prices using category-level averages rather than an overall dataset average
* Standardised values across gender, product category, and shopping mall fields
* Examined price distributions by product category
* Used skewness analysis to assess whether price transformations were required
* Checked category-level prices for potential outliers

The analysis found that category-level price distributions were generally not highly skewed and no significant price outliers were identified.

## Key Analysis & Findings

### Product Category Performance

Clothing was the highest-selling category and generated the highest sales. Shoes and Technology generated relatively high sales despite selling fewer units than some other categories, indicating higher revenue per unit.

Books and Souvenirs had the lowest quantities sold and consequently the lowest sales performance.

This suggests that sales volume alone does not explain revenue performance, as some categories generate more value from fewer transactions or units sold.

### Age & Spending Behaviour

The initial customer-level scatter plot showed no clear relationship between individual age and spending score. Spending appeared relatively consistent across individual ages, with no obvious correlation.

However, grouping customers into age brackets revealed a different pattern. Spending scores increased across the broader age groups, with customers aged **56+** showing the highest spending scores and the **18–24** group showing the lowest.

This demonstrates that segmenting customers into meaningful demographic groups can reveal patterns that may not be obvious when analysing individual observations.

### Gender & Spending

Spending behaviour was broadly similar between male and female customers. The box plot showed comparable spending distributions, including similar patterns of variation and outliers.

Based on this analysis, gender does not appear to be a strong differentiating factor for customer spending.

### Payment Method Preferences

Cash was the most commonly used payment method, followed by credit card and debit card.

The dominance of cash indicates that customers still have a strong preference for traditional payment methods. However, the significant use of cards also presents an opportunity to encourage card-based purchases through suitable promotional incentives.

### Monthly Sales Trends

Sales performance across **2021 and 2022 was relatively consistent throughout the available months**, although both years experienced lower sales in February.

2022 reached its peak in October, while 2021 recorded its highest sales in July.

For 2023, January sales were slightly lower than the previous two years, followed by a noticeable increase in February. March 2023 contained incomplete data, so the unusually low March sales should not be interpreted as an actual decline in performance.

## Business Recommendations

### 1. Strengthen Promotions During Low-Sales Periods

Use promotional campaigns during historically weaker months, particularly February, while leveraging high-performing categories such as Clothing, Shoes, and Technology to attract customers.

The increase in February 2023 could also be reviewed as a potential example of a successful promotional or sales strategy that could be adapted for other low-performing periods.

### 2. Target High-Value Product Categories

Technology and Shoes generated relatively strong sales despite lower unit volumes. Marketing these categories more strategically could help maximise revenue rather than focusing solely on products with the highest quantities sold.

### 3. Use Age-Based Customer Segmentation

The age-group analysis suggests that older customers tend to have higher spending scores. Marketing strategies can therefore be differentiated by age group rather than treating the entire customer base uniformly.

For products such as Technology and Shoes, customers aged approximately **26–45** could be considered an important target segment based on the project's analysis and recommendations.

### 4. Encourage Card Payments

Since cash remains the dominant payment method, the shopping mall could encourage greater credit card usage through discounts, promotions, or other payment incentives.

This could potentially increase purchase activity while also providing opportunities for more convenient transaction tracking.

### 5. Monitor Sales Trends Continuously

Monthly sales performance should be monitored against targets to identify changes in customer behaviour and detect periods requiring additional marketing activity.

Marketing campaigns should also be planned in advance and adjusted based on observed sales trends and customer preferences.

## Tools & Techniques

**Python**

* pandas
* NumPy
* Matplotlib
* Seaborn

**Analysis Techniques**

* Data cleaning and validation
* Missing-value treatment
* Duplicate detection
* Data standardisation
* Category-level imputation
* Distribution and skewness analysis
* Outlier detection
* Descriptive analysis
* Customer segmentation
* Correlation analysis
* Data visualisation
* Trend analysis

## Conclusion

The analysis shows that customer spending is influenced more clearly by product category and broader age segmentation than by individual age or gender. Clothing leads overall sales, while Shoes and Technology demonstrate strong revenue potential despite lower unit volumes.

The findings also highlight opportunities to improve sales through targeted promotions during weaker periods, age-based customer segmentation, stronger promotion of high-value categories, and incentives for card payments.
