# AB-testing
The Illusion of Improvement: A Funnel-Based Analysis of a Digital Marketing A/B Test
 Project Overview
This repository presents a statistical evaluation of a digital marketing A/B experiment comparing a Control and a Test campaign conducted in August 2019. The objective of the study is to examine whether improvements in engagement metrics translate into meaningful business outcomes.

While A/B testing is commonly used to optimize campaign performance, decisions are often based solely on surface-level metrics such as Click-Through Rate (CTR). This project adopts a full-funnel analytical approach to assess performance across engagement, conversion, and cost-efficiency stages.

Objectives
Compare Control and Test campaigns using statistical hypothesis testing
Evaluate performance across multiple funnel stages
Examine whether increased engagement leads to improved profitability
Emphasize rigorous, metric-specific statistical inference

Dataset Description
The dataset consists of 59 daily observations for each campaign and includes:
Impressions
Website Clicks
Purchases
Spend (USD)

Funnel indicators
Engagement and conversion metrics are treated as proportion-based outcomes, while cost metrics are treated as continuous variables.

Statistical Methodology

The analytical framework applies appropriate statistical techniques at each funnel stage:

1. Click-Through Rate (CTR)
Modeled as a binomial proportion
Two-sample Z-test for difference in proportions
Evaluated statistical significance at α = 0.05

2. Conversion Rate (CR)
Modeled as a binomial proportion
Two-sample Z-test for proportions
Assessed downstream purchase efficiency

3. Cost Per Purchase (CPP)
Treated as a continuous metric
Welch’s two-sample t-test applied to account for unequal variances
Degrees of freedom estimated using the Welch–Satterthwaite approximation

Key Findings:
The Test campaign achieved a statistically significant increase in CTR.
No statistically significant improvement was observed in conversion rate.
No significant reduction in cost per purchase was achieved.

These findings demonstrate that higher engagement does not necessarily imply improved profitability.

ightly more technical (for data science recruiters), or

Make a concise 8–10 line version optimized for portfolio visibility.
