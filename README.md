# mindspark-7-team-why-axis

Data source: https://osmhhelp.org/research
With more than 80% of U.S. workers reporting mental health challenges, and 54% of HR and benefits leaders reporting that their employees have higher expectations for mental health support, mental health benefits will continue to be key to workforce strategy in the tech industry

According to a survey conducted by Open-source mental health from 2014 to 2021 we found that approximately 1 in 2 people who need mental health are not seeking any kind of treatment due to various social stigmas and personal deterrents

We aim to use the aforementioned survey data and predict willingness to seek help for an employee on a scale of 1-100 so that HR’s can work on creating a conducive atmosphere for employees to encourage them for seeking medical help

Our initial step in approaching the problem is to collate survey data from multiple years and arrive at a master file. The questions asked in survey were not standard across years and this posed a data cleaning challenge. The information collected in survey can be broadly classified into employee demographics, company culture and social stigma indicators around mental health.

We chose specificity as a metric to minimize the risk of overlooking employees in need

After performing extensive EDA, we have a balanced dataset ready for modelling. We started with simple and heuristic logistic regression as a baseline model and eventually increased the complexity through advanced algorithms like random forest and multiple version of gradient boosting. We identified the top models and further tuned them using cross validation and grid search. We achieved a specificity of 90% with our random forest model.

Utilizing plotly dash we made an interactive and ready to deploy front end tool for HR’s which calculates employees inclination for seeking help.

For the future scope,  we believe collecting employee’s family and financial data can enhance the model. In long term, We can leverage wearable tech to collect data related to vitlas. 




