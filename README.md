# **A/B Testing Report: Click-Through Rate (CTR) for LunarTech CTA Button** 

## **Introduction:** 
This report analyzes the results of an A/B test conducted to evaluate the effectiveness of a new 
LunarTech call-to-action (CTA) button design. The experiment compared the click-through rate 
(CTR) of the new button (experimental group) against the existing button (control group). 

## **Data & Methodology:** 
• Data was retrieved from a CSV file containing user click data for both the control and 
experimental groups. 
• The Z-test for two proportions was used to statistically assess the difference in CTR 
between the groups. 
• Confidence interval (CI) was calculated to estimate the range of possible true differences 
in the CTR with a 95% confidence level. 
• Minimum detectable effect (MDE) of 10% was considered for practical significance.

## **Results:** 
**Group Statistics:** 
Group 
Control (con) 
Number of Users Clicks Click Probability (p_hat) 
N_con 
Experimental (exp) N_exp 
Export to Sheets 
X_con p_con_hat 
X_exp p_exp_hat 
Pooled Click Probability: p_pooled_hat 
Statistical Significance: 
• Significance level (alpha): 0.05 
• Test Statistic (Z-score): Test_stat 
• Z-critical value: Z_crit 
• P-value: p_value (rounded to 3 decimal places) 
The calculated p-value is compared to the chosen significance level (alpha). 
## **Hypothesis Testing:** 
• Null Hypothesis (H0): There is no statistically significant difference in CTR between the 
control and experimental groups. 
• Alternative Hypothesis (H1): There is a statistically significant difference in CTR 
between the control and experimental groups. 
**Decision:** 
• If p-value <= alpha: Reject H0, indicating a statistically significant difference. 
• If p-value > alpha: Fail to reject H0, suggesting the difference may be due to chance. 

## **Confidence Interval (CI):** 
The 95% CI provides a range within which the true difference in CTR between the groups is 
likely to lie. 
## **Practical Significance:** 
Based on the MDE of 10% and the calculated CI, we assess whether the observed difference is 
practically meaningful in addition to being statistically significant. 

## **Visualization:** 
A standard normal distribution with the rejection region for a two-tailed test is plotted. The test 
statistic and Z-critical values are highlighted. 

## **Conclusion:** 
Statistical Significance: P-value of the 2-sample Z-test: 0.0
There is statistical significance, indicating that the observed differences between the groups are unlikely to have occurred by chance alone. This suggests that the changes in the experimental group have a real effect compared to the control group.
Practical Significance: We had a practical significance! With MDE of 0.1, The difference between Control and Experimental group is practically significant. Lower bound of 95% confidence interval is: 0.04 

## **Recommendations:** 
• Based on the results, the observed difference in CTR warrants 
implementing the new CTA button design across the platform. 
 
## **Next Steps:** 
• Depending on the outcome, document the decision regarding the new CTA button design. 
• Implementing the new design, monitor its performance over time to ensure sustained 
positive impact. 
**Note:** Replace the bracketed placeholders with the actual values calculated in your code for a 
complete report. This report provides a framework for interpreting the A/B testing results and 
making informed decisions about the new CTA button design.
