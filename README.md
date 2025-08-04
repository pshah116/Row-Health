# Row Health Campaign Performance Analysis

# Table of Contents

• [Project Overview](#Project-overview)

• Insights Summary

• Recommendations

• Dashboard

• Technical Process and Caveats

## Project Overview

# The goal of this project is to investigate the performance of marketing campaigns at Row Health to surface recommendations on marketing budget allocation across future campaign categories

Founded in 2016, Row Health is a U.S.-based medical insurance provider serving thousands of customers. In 2019, they launched marketing campaigns centered on wellness education, affordability, and preventative care, supporting four plan tiers—bronze, silver, gold, and platinum—with varying premiums and coverage.

With a new data team in place and a renewed focus on strategic marketing, Row Health is looking to evaluate the effectiveness of its campaign categories. The primary goals are to boost customer signups and strengthen national brand awareness


## Dataset Structure
<img width="751" height="525" alt="2025-08-04_10h53_13" src="https://github.com/user-attachments/assets/4e2bcf61-f7ae-4db9-b823-cd8f6901055a" />

## Insights Summary

# North Star Metrics
To evaluate campaign performance, the insights primarily focused on the following key metrics:

• Impressions: The number of people who saw a marketing campaign.

• Cost per Person (CPP): the amount an advertiser pays each time a user clicks on their advertisement

• Signup Rate: The percentage of people who see a campaign and ultimately signed up for a Row Health plan.

• Cost per Signup (CPS): The average dollars spent in order to acquire a signup from each campaign.

• Click through Rate (CTR): The percentage of people who see a campaign and click on the associated link.

• Signup Count: Total number of signups achieved throughout the entire timeframe of 2019-2023 

# Marketing Insights
• Tailored Health Plans campaign generated the highest number of impressions (1.3M+), yet it recorded the second-lowest click-through rate (7%), suggesting a possible disconnect between the audience targeted and the campaign’s call-to-action

• The Healthy Living and Tailored Health Plans campaigns have similar total impressions (1.37M vs. 1.40M), but differ significantly in performance—Healthy Living delivers a higher click-through rate (10% vs. 7%) and a slightly lower cost per click ($0.05 vs. $0.06)

• The Golden Years Security campaign has the lowest click-through rate at just 1%, leading to very few clicks despite its cost and resulting in a significantly high cost per click of $0.68. In comparison, the other campaigns demonstrate more efficient budget use, with CPPs ranging from $0.03 to $0.11

• Among all categories, Health for All and Benefit Updates significantly outperformed the average click-through rate (9%), achieving rates of 25% and 22%—roughly three times higher than the overall average

# Signup Insights
• During the 2020 pandemic, heightened demand for healthcare products led to a surge in signups across all campaign categories. Although this momentum carried into early 2022, most categories began to see a downturn in signup numbers, with recent figures dipping below pre-pandemic levels. Notably, Coverage Matters and HealthyLiving have remained strong performers, together making up close to 50% of the most recent signups

• The Health For All campaign category delivered the strongest results, generating over 3,500 signups and a 2% signup rate—roughly 12 times higher than the overall average. This exceptional performance is largely driven by the Health Awareness campaign type, which recorded the highest signup rate among all types at 2.78%

• Golden Years Security has the lowest signup count (23) and a horrific signup rate (0.01%) despite having the highest cost per signup ($176.73)

• Although the Benefit Updates campaign achieved the second highest click-through rate, it resulted in only 45 signups—the second lowest among all categories—and a signup rate of just 0.02%. Additionally, it had the second highest cost per signup at $47, indicating limited conversion efficiency

• Interestingly, the #HealthyLiving campaign generated the highest total signups, yet its signup rate remained relatively low at just 0.27%.

• The two campaign categories with the highest cost per signup—Golden Years and Benefit Updates—were primarily driven by informational campaign types, such as offers and policy details, which contributed to their elevated acquisition costs

# Claims Insights
• While most campaign categories saw claim volumes and amounts stabilize after an initial surge during the pandemic in 2020, the Compare Health Coverage campaign showed a different trend—experiencing showing consistent increase in claims through 2021 and early 2022, reaching a peak of $173K in July 2022 before sharply declining in subsequent months as claim counts dropped 

• The Compare Health Coverage campaign resulted in the highest overall claim costs, with customers averaging $410 per claim and generating a total claim amount of $3.9 million

• A trend to be noticed is that generally with more signups achieved more claims will be filed, this is inevitable due to the fact that the more customers there are on an insurace policy the greater the chance there is for a higher number of claims. Two of the top three campaign categories with the highest number of claims also provided the highest number of signups (Healthy Living and Health For All)

## Recommendations
Recommendations center on two key strategies: eliminating underperforming campaign categories and redirecting budget to those demonstrating stronger results across core performance metrics

• Golden Years Security should be evaluated for discontinuation or major revision, given its poor performance—just a 1% click-through rate and a steep $176 cost per signup. A more effective return on investment (ROI) would be to shift its budget toward the Health For All campaign, which demonstrates far greater efficiency with a 25% CTR and a 2% signup rate

• Tailored Health Plans: Explore why this campaign generated the highest number of impressions but failed to convert clicks—this may point to campaign execution issues or gaps in the available data that need to be addressed.

• Compare Health Coverage: Conduct a thorough review of this campaign’s target audience and health-related behaviors to determine whether it’s unintentionally drawing in higher-risk individuals than originally intended

• Health Awareness: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.

• COVID Campaigns: Examine the unusually high cost per signup for COVID-related campaigns, where just 2 signups resulted in over $1K in spend—significantly above the $3.70 average. Consider phasing out these campaigns due to their inefficiency

## Dashboard
The dashboard can be found in Tableau Public [HERE](https://public.tableau.com/app/profile/prerak.shah4558/viz/RowHealthDashboard_17533905682670/Dashboard2) This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.
<img width="1291" height="996" alt="2025-08-04_12h59_22" src="https://github.com/user-attachments/assets/6fc73c99-db52-47ad-9d10-fcf36958cfb3" />


