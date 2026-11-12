# 📊 Telecom Customer Churn Analysis | Microsoft Excel

<p align="center">
  <b>Customer Analytics • Business Intelligence • Data Analysis</b>
</p>

---

## 🎯 Project Overview

Customer churn is one of the major challenges faced by telecommunications companies. Losing customers can negatively impact revenue, market share, and long-term business growth.

This project analyzes customer churn patterns using **Microsoft Excel**, based on a telecommunications case study involving Airtel.

The objective is to identify customer characteristics, service usage patterns, and other factors associated with customer churn and translate the findings into actionable business recommendations.

## 🏢 Business Problem

The telecommunications business has observed customers discontinuing their services. Management wants to understand:

- How many customers are leaving?
- Which customer groups have higher churn rates?
- Does service usage influence customer retention?
- Are customer service interactions associated with churn?
- What actions could help improve customer retention?

## 🎯 Project Objectives

1. Measure the overall customer churn rate.
2. Compare churn across customer segments.
3. Analyze the relationship between service usage and churn.
4. Identify customer behavior patterns associated with higher churn.
5. Recommend possible customer retention strategies.

## 🛠️ Tools & Techniques

| Tool / Technique | Application |
|---|---|
| Microsoft Excel | Data analysis and reporting |
| Pivot Tables | Customer segmentation and aggregation |
| Pivot Charts | Visual comparison of customer groups |
| Descriptive Statistics | Average usage and charge comparisons |
| Percentage Analysis | Customer churn rate calculation |
| Correlation Analysis | Exploring relationships between variables |
| Data Categorization | Grouping customers by usage levels |

## 📁 Repository Structure

```text
Telecom-Customer-Churn-Analysis-Excel/
│
├── Excel/
│   ├── Telecom_Customer_Churn_Analysis.xlsx
│   └── README.md
│
└── README.md
```

## 📂 Dataset Overview

The dataset contains **4,250 customer records** and includes demographic, account, subscription, and service usage information.

| Category | Variables |
|---|---|
| Customer Information | State, Account Length, Area Code |
| Subscription Details | International Plan, Voice Mail Plan |
| Day Usage | Day Minutes, Calls, Charges |
| Evening Usage | Evening Minutes, Calls, Charges |
| Night Usage | Night Minutes, Calls, Charges |
| International Usage | International Minutes, Calls, Charges |
| Customer Support | Number of Customer Service Calls |
| Target Variable | Churn (Yes/No) |

**Target variable:** Churn indicates whether a customer discontinued the service.

## 📈 Analysis & Detailed Findings

The workbook organizes the case study into basic, medium, and advanced analytical questions.

# 🟢 1. Basic-Level Analysis

### Q1. How many customers have churned, and what is their proportion compared to the total customer base?

**Analysis:** Customer count and percentage were calculated using the churn variable.

| Customer Status | Customers | Percentage |
|---|---:|---:|
| Non-Churned | 3,652 | 85.93% |
| Churned | 598 | 14.07% |
| **Total** | **4,250** | **100%** |

**Finding:** Approximately 14.07% of the customers have churned.

**Business Insight:** The churn rate provides a baseline for evaluating future retention initiatives. Reducing customer losses can help protect recurring business revenue.

### Q2. What is the average account length for churned customers compared to non-churned customers?

**Analysis:** Average account length was compared across churn categories.

| Customer Status | Average Account Length |
|---|---:|
| Non-Churned | 99.92 months |
| Churned | 102.14 months |

**Finding:** The difference in average account length is relatively small. In this dataset, account length alone does not appear to be a strong differentiator of churn.

**Business Insight:** Retention strategies should consider additional variables such as customer service experience, pricing, and usage behavior rather than relying only on customer tenure.

### Q3. How does subscription to international plans correlate with customer churn?

**Analysis:** Churn rates were compared between customers with and without international plans.

| International Plan | Churned | Total Customers | Churn Rate |
|---|---:|---:|---:|
| Yes | 167 | 396 | 42.17% |
| No | 431 | 3,854 | 11.18% |

**Finding:** Customers subscribed to international plans have a substantially higher churn rate.

**Business Insight:** The company could review international calling prices, plan benefits, and customer usage patterns. More competitive international bundles may help improve retention.

### Q4. Is there a significant difference in customer service calls between churned and non-churned customers?

**Analysis:** Average customer service calls were calculated for both groups.

| Customer Status | Total Service Calls | Average Calls |
|---|---:|---:|
| Non-Churned | 5,265 | 1.44 |
| Churned | 1,361 | 2.28 |

**Finding:** Churned customers make more customer service calls on average than non-churned customers.

**Business Insight:** Repeated customer service interactions may indicate unresolved issues or dissatisfaction. The company should identify recurring complaints and improve first-contact resolution.

*Note: These are descriptive comparisons, not a formal statistical significance test.*

### Q5. Do day, evening, and night call charges differ between churned and non-churned customers?

**Analysis:** Average call charges were compared across churn categories.

| Average Charge | Non-Churned | Churned |
|---|---:|---:|
| Day Charges | 29.84 | 35.53 |
| Evening Charges | 16.88 | 17.85 |
| Night Charges | 8.98 | 9.29 |

**Finding:** Day charges show the largest difference between churned and non-churned customers. Evening and night charges show smaller differences.

**Business Insight:** Higher day charges may be associated with increased churn. Reviewing day-time pricing and usage-based packages could help address potential customer concerns.

### Q6. What is the relationship between total day minutes and churn?

**Analysis:** Average day minutes were compared between customer groups.

| Customer Status | Average Day Minutes |
|---|---:|
| Non-Churned | 175.56 |
| Churned | 208.99 |

**Finding:** Churned customers have higher average day-time usage than non-churned customers.

**Business Insight:** Higher day-time usage may increase exposure to usage-related charges. The company could consider usage-based alerts and suitable calling packages for high-usage customers.

### Q7. How does having a voice mail plan affect churn rates?

**Analysis:** Churn rates were compared for customers with and without voicemail plans.

| Voice Mail Plan | Churned | Total Customers | Churn Rate |
|---|---:|---:|---:|
| Yes | 82 | 1,112 | 7.37% |
| No | 516 | 3,138 | 16.44% |

**Finding:** Customers with voicemail plans have a lower churn rate than customers without voicemail plans.

**Business Insight:** Additional service features may contribute to customer engagement and retention. The company could explore suitable value-added service bundles.

### Q8. Are higher international minutes and charges associated with higher churn?

**Analysis:** Average international usage and charges were compared.

| Metric | Non-Churned | Churned |
|---|---:|---:|
| International Minutes | 10.19 | 10.63 |
| International Charges | 2.75 | 2.87 |

**Finding:** Churned customers have slightly higher average international minutes and charges. The differences are relatively small compared with the differences observed in day usage.

**Business Insight:** International usage and pricing may be worth investigating further, especially among customers subscribed to international plans.

### Q9. Is there a correlation between total day calls and churn?

**Analysis:** Average total day calls were compared.

| Customer Status | Average Day Calls |
|---|---:|
| Non-Churned | 99.81 |
| Churned | 100.48 |

**Finding:** The average number of day calls is very similar across the two groups. The difference is small and does not suggest a strong relationship on its own.

**Business Insight:** Call frequency alone may not explain churn. Usage duration and associated charges may provide more useful information.

### Q10. Compare average evening charges for churned vs. non-churned customers.

**Analysis:** Average evening charges were compared.

| Customer Status | Average Evening Charges |
|---|---:|
| Non-Churned | 16.88 |
| Churned | 17.85 |

**Finding:** Churned customers have slightly higher average evening charges.

**Business Insight:** Evening charges may contribute to customer dissatisfaction for some segments, but a formal statistical test would be needed to determine whether the difference is significant.

# 🟡 2. Medium-Level Analysis

### Q1. Is there a particular area code with a higher churn rate?

**Analysis:** Customer churn was segmented by area code.

| Area Code | Total Customers | Churned Customers | Churn Rate |
|---|---:|---:|---:|
| 408 | 1,086 | 152 | 13.996% |
| 415 | 2,108 | 287 | 13.614% |
| 510 | 1,056 | 159 | 15.057% |

**Finding:** Area code 510 has the highest churn rate, at approximately 15.06%. The differences between area codes are relatively small.

**Business Insight:** The company could investigate whether local service quality, customer demographics, or regional pricing differences contribute to the variation.

### Q2. How does the number of customer service calls relate to churn at different thresholds?

**Analysis:** Customers were grouped into low, medium, and high customer service call categories in the workbook.

| Service Call Category | Churned | Total Customers | Churn Rate |
|---|---:|---:|---:|
| Low | 428 | 3,915 | 10.93% |
| Medium | 160 | 318 | 50.31% |
| High | 10 | 17 | 58.82% |

**Finding:** Churn rates increase substantially across the medium and high service-call categories.

**Business Insight:** Customers making repeated service calls should be identified for proactive support and issue resolution.

### Q3. Are newer customers more likely to churn?

**Analysis:** Customers were divided into tenure categories.

| Account Length Category | Churn Rate |
|---|---:|
| New | 11.36% |
| Medium | 15.01% |
| Old | 13.83% |
| Legacy | 13.76% |

**Finding:** The medium-tenure segment has the highest churn rate in the workbook's categorization. New customers do not have the highest churn rate.

**Business Insight:** Retention campaigns should not focus exclusively on new customers. Medium-tenure customers may also need targeted engagement.

### Q4. What is the impact of international call charges on churn among international-plan subscribers?

**Analysis:** Customers with international plans were segmented by international charge category.

| International Charge Category | Churned | Total Customers | Churn Rate |
|---|---:|---:|---:|
| High | 126 | 271 | 46.49% |
| Low | 41 | 125 | 32.80% |

**Finding:** Customers in the high international-charge category have a higher churn rate than those in the low-charge category.

**Business Insight:** Reviewing international pricing and offering suitable bundles may help reduce churn among high-charge customers.

### Q5. How do evening usage patterns relate to customer churn?

**Analysis:** Evening call usage and evening charges were categorized into usage levels.

**Evening call usage**

| Usage Category | Churn Rate |
|---|---:|
| High | 13.64% |
| Low | 8.33% |
| Medium | 14.53% |
| Very High | 16.67% |

**Evening charges**

| Charge Category | Churn Rate |
|---|---:|
| High | 14.91% |
| Low | 7.23% |
| Medium | 12.44% |
| Very High | 20.09% |

**Finding:** Very high evening usage and very high evening charges have the highest churn rates within their respective categories.

**Business Insight:** High evening usage customers could be offered more suitable calling plans or targeted pricing packages.

### Q6. Can customer usage patterns identify distinct customer groups?

**Analysis:** The workbook categorizes customers by day, evening, night, and international usage levels.

Some observations:

- Day-time very high usage has a particularly high churn rate of approximately 81.03%.
- Evening very high usage has a churn rate of approximately 27.88%.
- Night usage categories show comparatively smaller differences.
- International very high usage has a churn rate of approximately 18.12%.

**Finding:** Usage-based categories help highlight customer segments with different churn patterns.

**Business Insight:** High-usage customers could be monitored for pricing concerns and offered tailored packages.

*Note: This is usage-category segmentation, not a formal K-means or hierarchical clustering model.*

### Q7. How does voicemail usage interact with churn?

**Analysis:** Customers with voicemail plans were segmented by voicemail message usage.

| Voicemail Usage | Churned | Total Customers | Churn Rate |
|---|---:|---:|---:|
| High | 41 | 461 | 8.89% |
| Low | 1 | 43 | 2.33% |
| Medium | 38 | 586 | 6.48% |
| Very High | 2 | 21 | 9.52% |

**Finding:** The very-high-usage category has the highest churn rate, but it contains only 21 customers. The high-usage group also has a relatively higher churn rate than the low-usage group.

**Business Insight:** The company could explore whether high voicemail usage reflects customer needs that are not adequately served by existing packages.

### Q8. Is there a point of inflection where higher day usage leads to higher churn?

**Analysis:** The case study asks for a scatter plot comparing total day minutes, day charges, and churn.

**Finding:** The dataset shows higher average day minutes and day charges among churned customers. However, the workbook does not establish a statistically validated tipping point.

**Business Insight:** A scatter plot with churn categories and a more detailed threshold analysis could help investigate whether unusually high usage is associated with increased churn.

### Q9. Does international call frequency affect churn differently for customers with and without international plans?

**Analysis:** Churn was compared across international-plan status and international-call usage categories.

- Customers without an international plan have an overall churn rate of approximately 11.18%.
- Customers with an international plan have an overall churn rate of approximately 42.17%.

**Finding:** International-plan subscribers have substantially higher churn across the overall comparison. Within each plan group, the call-frequency categories show variation, but some categories have small sample sizes.

**Business Insight:** The company should investigate the pricing, suitability, and perceived value of international plans.

### Q10. Do different customer service call reasons indicate churn risk?

**Analysis:** The available dataset contains the number of customer service calls but does not contain detailed reasons for those calls.

**Finding:** This question cannot be answered using the available dataset.

**Business Insight:** Additional data on complaint categories, billing issues, network problems, and service requests would be needed to investigate this question.

# 🔴 3. Advanced-Level Analysis & Limitations

### Q1. Can a predictive model identify customers likely to churn?

**Proposed approach:** The case study suggests logistic regression to estimate churn likelihood and interpret predictor coefficients.

**Status:** A logistic regression model has not been implemented in this Excel workbook.

**Potential business application:** A validated model could help prioritize high-risk customers for retention campaigns.

### Q2. Can time-series analysis identify churn trends and seasonality?

**Limitation:** The available dataset does not contain a suitable customer churn date or time-period variable.

**Status:** Time-series trend and seasonality analysis cannot be performed reliably with the available data.

### Q3. Can clustering identify distinct customer groups?

**Proposed approach:** K-means or hierarchical clustering could be applied using customer usage and demographic variables.

**Status:** The workbook uses categorized usage groups rather than implementing a formal clustering algorithm.

### Q4. What are the interaction effects between customer attributes?

**Proposed approach:** Investigate combinations such as international-plan subscription and international usage.

**Status:** The workbook includes segmented comparisons, but does not provide a formal multivariate interaction model.

### Q5. What is the economic impact of customer churn?

**Analysis:** The workbook calculates total charges using:

Day Charges + Evening Charges + Night Charges + International Charges

| Customer Status | Total Calculated Charges |
|---|---:|
| Non-Churned | 213,488.03 |
| Churned | 39,188.24 |
| **Total** | **252,676.27** |

**Finding:** The churned customer group accounts for approximately 15.51% of the total calculated charges.

**Limitation:** The dataset does not specify whether these charges represent daily, monthly, or another billing period. Therefore, they should not be interpreted as annual revenue loss, ARPU, or customer lifetime value without additional billing information.

# 💡 4. Key Business Insights

Based on the available dataset and analysis:

1. **Overall churn:** 14.07% of customers have churned.
2. **International plans:** Subscribers have a much higher churn rate than non-subscribers.
3. **Customer support:** Churned customers make more customer service calls on average.
4. **Day usage:** Churned customers have higher average day minutes and day charges.
5. **Voicemail plans:** Subscribers have a lower churn rate than non-subscribers.
6. **Evening charges:** Very high evening-charge customers show a higher churn rate within the categorized groups.
7. **Geographic segmentation:** Area code 510 has the highest churn rate among the three area codes, although the difference is modest.

## 🚀 5. Business Recommendations

| Identified Pattern | Recommended Action |
|---|---|
| High international-plan churn | Review international pricing and bundles |
| Higher service calls among churned customers | Improve complaint resolution and customer support |
| Higher day usage among churned customers | Offer usage-based packages and alerts |
| Lower churn among voicemail subscribers | Promote relevant value-added services |
| Higher churn in very-high evening-charge group | Review evening pricing and package suitability |
| Variation across area codes | Investigate regional customer experience |

## 📚 6. Skills Demonstrated

- Microsoft Excel
- Data Cleaning and Preparation
- Pivot Table Analysis
- Customer Segmentation
- Descriptive Statistics
- Churn Rate Calculation
- Data Interpretation
- Business Problem Solving
- Data-Driven Recommendations

## 📎 7. Project Files & References

**Excel Solution Workbook:** [View the Excel analysis](Excel/Telecom_Customer_Churn_Analysis.xlsx)

**Case Study Dataset:** [Kaggle – Customer Churn Prediction](https://www.kaggle.com/competitions/customer-churn-prediction-2020/data)

## 👨‍💻 Project Information

**Project:** Telecom Customer Churn Analysis  
**Domain:** Telecommunications / Business Analytics  
**Tool:** Microsoft Excel  
**Analysis Type:** Exploratory Data Analysis and Customer Segmentation

---

⭐ If you find this project useful, feel free to explore the workbook and its analysis.
