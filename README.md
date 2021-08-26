# Data-Visualisation-
Project on data visualisation via Python and Tableau. I have applied data visualization techniques that I have learned throughout the module to undertake this analysis. You may use any kind of data visualizations that you deem appropriate. However, I have prefered to demonstrate application of UMAP dimensionality reduction in the analysis of both datasets. All visualizations are relevant to the task at hand.

In this work, I assume that I am a world class data analysts works at an automotive insurance company. The data science department has tasked me with visual analysis of two datasets.

## Dataset 1: Claims.csv
This dataset contains information about insurance claims. It has 21 variables. A short explanation of some variables is provided in Appendix1.

## Dataset 2: Collisions.csv
This dataset contains information about road accidents involving vehicle-to-vehicle collisions. It has 13 variables, all of which are self-explanatory.

1. Based on dataset 1, can we say which factors could be used to identify fraudulent claims?
2. Based on dataset 2, can we say which factors contribute to severe vehicle damage?



## Appendix 1: Relevant Information about some variables in Claims.csv

‘policy_csl’: CSL stands for Combined Single Limit. It is a type of auto insurance policy that covers bodily injury and property/vehicle damage for each passenger for each accident, and that includes bodily injury and property/vehicle damage sustained by the other party. In this column, a value of ‘250/500’ means that policy allows a maximum payment of €250,000 per person per accident and a total of €500,000 per accident.

‘policy_deductible’: the amount (€) that the insured must pay towards the costs in an insurance claim before the insurance coverage kicks in. This means that:
Compensation to the insured = ‘total_claim_amount’ – ‘policy_deductible’

‘policy_annual_premium’: the amount (€) that the insured pays per year for the insurance policy.

‘umbrella_limit’: limit of the umbrella insurance policy, if the insured has bought one. Umbrella insurance policy is the excess liability insurance on top of the base insurance policy. It provides coverage after the base insurance policy limit has been exhausted. A value of ‘0’ in this column indicates that the insured does not have an umbrella policy. On the other hand, a value of ‘1,000,000’ indicates that the insured has an excess coverage of a million euros if the base policy limit is exhausted.

‘insured_relationship’: driver’s relationship with the insured.

