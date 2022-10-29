# Telecom churn analysis of multinational French company Orange SA

Problem Statement: French multinational company is facing the churn problem. I was asked to figure out the key features effecting the churn increase from the 
given data-set and suggest the possible solutions 

Given: Clean customer data in .csv format, which includes key features as number of international calls, total day-call minutes, calling chargers etc. 

Tools/modules (python) used: This project has mostly used: i) pandas for .csv data; ii) Matplotlib, and iii) Seaborn for data visualization. Data overview: The csv data provided consist of 20 columns and 3333 row entries of customers. No Nan value was found. Nearly 14.5% of the customers were having churn value as true, which is not a good sign for sustainable growth. Based on the correlation heat map with churn, i) Customer service call, ii) Total day-call minutes &, iii) Total day chargers are having the highest influence on churn (correlation coefficient > 0.2). 

Result summary: From this data exploration study, following conclusion can be made: 
- New Jersey (NJ), California, Texas, Mary Land (MD), South Carolina (SC) and New York requires a network upgradation. 
- As the day-call numbers are increasing beyond the 100 churn is also increase (median and average for the churn = True is higher). 
- Customers with total day-calling minutes greater than 225 (approx.) are switching their network, because they might be facing more call drops/noise/connection issues. 
- Customers are switching the network when then are paying higher sum of money (approx. 35$ median; or higher). 
- Customers calling service help for more than 5 times are showing high churn. Indicating that their issues were not resolved. 
- When the number of Voice messages are greater than 20, there is very high chance for the churn. 
- Not many customers are using international callings but among the using customers churn percentage is very high i.e., more than 40%.
