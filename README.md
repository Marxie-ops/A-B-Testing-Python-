# **A/B Testing and Hypothesis Testing in Click-Through Rate (CTR) Analysis**
This project demonstrates an A/B test conducted to determine whether a change in the experimental group had a statistically significant effect on click-through rates (CTR) compared to a control group.

## **Table of Contents**

**Project Overview**

**Hypothesis**

**Significance Level (Alpha)**

**Steps to Calculate Critical Values and P-Values**

**Parameters from Power Analysis**

**Test Results**

**Conclusion**

## **Project Overview**
In this A/B testing project, we aim to analyze if there is a statistically significant difference between the control and experimental groups in terms of click-through rates (CTR). The project covers all essential steps of hypothesis testing, calculation of critical values and p-values, and analysis of results for both statistical and practical significance.

## **Hypothesis**
**Null Hypothesis (H0):** There is no difference in CTR between the control and experimental groups.
Alternative Hypothesis (H1): There is a difference in CTR between the control and experimental groups.
**Significance Level (Alpha)**
Alpha: The significance level is set at 0.05 (5%), meaning there is a 5% risk of rejecting the null hypothesis when it is true (Type I error).

**Steps to Calculate Critical Values and P-Values**
Choose a Significance Level (Alpha): Set at 0.05.
Determine the Appropriate Test Statistic: We chose a z-test as we are comparing proportions.

**Calculate the Test Statistic:**
Number of clicks in Control: 1989

Number of clicks in Experimental: 6116

Total number of users in each group: 10,000

**Calculate Click Probabilities:**
Click Probability in Control Group: 0.1989

Click Probability in Experimental Group: 0.6116

**Calculate Pooled Estimate:**
Pooled Click Probability: 0.40525

**Calculate Standard Error and Test Statistic:**
Standard Error: 0.00694

Test Statistic (Z-score): -59.44

**Find the Critical Value:**
Z-critical value from Standard Normal distribution at 5% significance: 1.96

**Compare Test Statistic to Critical Value:**
Since the test statistic (-59.44) falls well beyond the critical value (±1.96), we reject the null hypothesis.

**Calculate the p-value:**
P-value: 0.0
Since the p-value (0.0) is below our alpha level (0.05), there is strong evidence against the null hypothesis, indicating a statistically significant difference between the two groups.

**Parameters from Power Analysis**
Beta (Type II Error Probability): Low beta values increase the power but also increase the risk of failing to detect a real effect.
Power (1 - Beta): Probability of correctly rejecting the null hypothesis.
Delta (Minimum Detectable Effect): 0.1
Alpha (Significance Level): 0.05

## **Test Results**
Control Group:
Users: 10,000
Clicks: 1989
Click Probability: 0.1989

Experimental Group:
Users: 10,000
Clicks: 6116
Click Probability: 0.6116
Pooled Click Probability: 0.40525

Standard Error: 0.00694
Z-Test Statistic: -59.44
Z-critical Value: 1.96
P-value: 0.0
**Confidence Interval: [0.399, 0.426]**
## **Conclusion**
The results show a statistically significant difference between the control and experimental groups at the 5% significance level. Given the p-value of 0.0, we reject the null hypothesis, concluding that the change in the experimental group has a real effect on the click-through rate compared to the control group.

**Furthermore, the confidence interval ([0.399, 0.426]) and the minimum detectable effect (MDE) of 0.1 confirm that this difference is also practically significant.**

