# ML_BANK
Predict if the client will subscribe to a term deposit based on the analysis of the marketing campaigns the bank performed.
# Business Use Case
There has been a revenue decline for a Portuguese bank and they would like to know what actions to take. 
After investigation, they found out that the root cause is that, their clients are not depositing as frequently as before. 
Knowing that term deposits allow banks to hold onto a deposit for a specific amount of time, so banks can invest in higher gain financial products to make a profit.
In addition, banks also hold better chance to persuade term deposit clients into buying other products such as funds or insurance to further increase their revenues. 
As a result, the Portuguese bank would like to identify existing clients that have higher chance to subscribe for a term deposit and focus marketing efforts on such clients.
# Potential Business Problems
Run optimized campaigns to bring in more customers, and thereby increase the bank revenue ?
Increase long-term holdings which can be further invested in different financial instruments? 
# Why solve this problem? 
Business Impact
Improve prediction - identify common features of subscribing customers - targeted campaigns
Improve prediction - identify right target audience- efficient budget for marketing
# Models and Approaches: 
Logistic Regression > AUC_ROC: 67.17 % After tuning AUC_ROC:72.4 %
Random Forest Classifier>AUC_ROC: 68.01 % After tuning AUC_ROC:92.48 %
XGBoost Classifier > AUC_ROC:  68.19 % After tuning AUC_ROC:93.81 %

""" Final Results: From the above observations it can be inferred that the best performing model was XGBoost giving an AUC_ROC score of 93.81 %. 
While XGBoost is used a lot, it is always prudent to start from simpler algorithms and then go to complex ones."""
Insights & Decisions 
# Customers to be targeted :
Age : 30–50 
Education : University, High School, Professional Courses 
Job : Admin, Blue-collar, Technician
# Campaign Targets :
Customers who were not targeted before
Customers successful in previous campaigns 
Plan campaigns from May through August



# credits
Thanks GreyAtom for giving hands-on experience on this project,great platform to learn Data Science.
# FOR article 
MEDIUM LINK https://medium.com/@tejashree-nawale/machine-learning-project-2bfeeccad68b
