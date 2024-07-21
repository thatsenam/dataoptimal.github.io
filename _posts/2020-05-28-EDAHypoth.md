---
title: "Exploratory Data Analysis and Hypothesis Testing"
date: 2020-05-28

header:
  image: "/images/EDA3.jpg"
  teaser: "/images/net2.png"
excerpt: "EDA, Hypothesis Testing, Phython"
mathjax: "true"
---

## Automobile Insurance Claim Fraud Factors
**Overview**

This project used exploratory data analysis and statistical techniques in Python to prove or disprove a hypothesis based on automobile claims fraud variables.

**Statistical Questions**

* What variables in the auto insurance claim records show a distinction between fraudulent claims and non-fraudulent claims?
* Do the values of variables in observations in which fraud was reported differ statistically from the values of variables in observations in which no fraud was reported?

**Hypotheses**

* There is no difference in the means of variables in the fraud reported subset and the same variables in the fraud not reported subset.  
* There is no significant linear relationship between the fraud reported target variable and any of the claim transaction variables.

**Data**

[Claims](https://www.kaggle.com/patilk1/fraudulentinsuranceclaim){:target="_blank"}

**Techniques**

* Histograms
* Descriptive statistics
* Probability mass function
* Cumulative distribution function
* Probability plot
* Scatter plots
* Point-Serial Correlation
* Permutation tests

**Distinctive Variables**

_Incident Severity_

68% of fraud reported cases claimed Major Damage but only 14% of fraud not reported cases claimed Major Damage.

![Severity](/images/claims/Severity.PNG)


_Witnesses_

Fraud reported cases have higher means and quartiles for number of witnesses at every checkpoint. 

![Witnesses](/images/claims/Witnesses.PNG)


_Total Claim Amount_

Fraud reported cases have higher means and quartiles for total claim amounts at every checkpoint. 

![Amounts](/images/claims/Amounts.PNG)


_Hobbies_

The claimant's hobbies show some variation in fraud cases.

![Hobbies](/images/claims/Hobbies.PNG)


_Umbrella Limit_

The p-value from point-biserial correlation indicates that the umbrella limit variable may be significant.


**Outcome**

Through statistical analysis and hypothesis testing, I rejected the null hypothesis that there is no difference in the means of Total Claim Amount variable in the fraud reported subset versus the fraud not reported subset, but concluded that it is plausible that the observed difference in means between the other variables in the fraud reported subset and the fraud not reported subset are just the result of random sampling and rejected the null hypothesis for all variables other than the Total Claim Amount variable.

Regarding the hypothesis that there is no significant linear relationship between the fraud reported target variable and any one of the claim transaction variables, the correlation hypotheses testing showed that the null hypothesis should be accepted as none of the p-values of the claim transactions variables were statistically significant. 

**Resources**

This analysis utilizes supported code from Allen Downey's ThinkStats2 [ThinkStats2](https://github.com/AllenDowney/ThinkStats2){:target="_blank"}

### The Complete Project: [here](https://github.com/MaryDonovanMartello/EDA-and-Hypothesis-Testing){:target="_blank"}.
