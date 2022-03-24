# Analyze_ab_test_results-project
A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these

For this project, we will be working to understand the results of an A/B test run by an e-commerce website. Our goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.


# Conclusions

Based on A/B test results, we fail to reject the null hypothesis as there is no statistically significant change in conversion rates of the experiment group that received the new page as compared to that of the control group that received the old page. Applying logistic regression shows that the new page is not statistcally significant in predicting the probability of conversion. Additionally, the inclusion of the country or the interaction between country and new page in logisitic regression also shows no statistical significant impact on predicting conversion likelihood. Consequently, I do not recommend applying the new page.
