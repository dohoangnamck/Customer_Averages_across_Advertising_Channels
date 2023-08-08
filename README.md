# Customer_Averages_across_Advertising_Channels
Determine Customer Averages across Advertising Channels using Hypothesis testing

## CASE 
An e-commerce company makes advertising on 3 platforms YouTube, Instagram, and Facebook. However, does the director care about the average number of users obtained through different channels? So, the number of users interacting through the channels recorded over 15 days is as follows:

Based on the data collected, determine whether there is a difference in customer averages across advertising channels using hypothesis testing, with significance alpha=5%

To determine if there is a difference in average customers across advertising channels using a hypothesis test, follow these steps:

* Validate the normality assumption: Conduct a Shapiro-Wilk test to evaluate whether the data for each ad channel follows normal delivery. If the data is not normally distributed, consider applying a transformation or using a non-parametric test instead.

* True equality of variances: Use Levene's Test to determine if the variance of the average customer across the advertising channels is equal. If the assumption of equal variances is violated, consider using alternative tests such as Welch's ANOVA or the Kruskal-Wallis test.

* Perform ANOVA: Apply the F-test within the ANOVA framework to assess whether the average customer medium across advertising channels is significantly different. If the p-value associated with the F-test is lower than the predefined level of significance, conclude that there is a significant difference in the average of the customers across the advertising channels.

* Analyze which group is really different with posthoc_mannwhitney
