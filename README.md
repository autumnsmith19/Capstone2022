# Data Science Capstone Project: What Impacts the Cost of Healthcare?
<i>Autumn Smith</i>

It is no secret that healthcare inequality exists in the United States, and that healthcare costs tend to be high. The aim of this project is to consider how much an individual may pay for healthcare, given certain characteristics. Specifically, I look at the costs an individual pays, on top of insurance costs, for healthcare services in the year 2017, and the features that impact said cost. 

To investigate my question, I used a dataset consisting of 81 columns and 31,880 rows from IPUMS Health Surveys. Specifically, I used the IPUMS MEDICAL EXPENDITURE PANEL SURVEY, which is a set of large-scale surveys of families and individuals, their medical providers, and employers across the United States that is implemented through the Department of Health and Human Services.

To determine which features had a significant impact, I built a linear regression model that ran on 10 features. To determine the features used in the model, I used stepwise regression and VIF scores with a cutoff threshold of 5 to address any issues of multicollinearity. 
