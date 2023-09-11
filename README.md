# BFSI
# Problem statement:
The objective is to build a statistical model to estimate borrowers’ LGD(Loss given default). 
LGD = ( Loan amount – (Collateral value + Total repayment done) )/ Loan amount 
Business Goal:
Develop a model that can estimate borrowers’ LGD.
# Steps:
• Business Understanding 
• Data Understanding & cleaning 
• Data visualization and EDA 
• Data Preparation 
• Model Building 
• Model Evaluation 
# Findings:
XGBoost With Hyperparameter tuning has given the best accuracy score.
###### The key features selected by the model are as follows – 
▪ Vintage_in_months : The model considers vintage_in_months as a significant predictor for predicting lower losses given default for customers with longer relationships with the institution. 
▪ No of loans : Customers with a higher number of loans may exhibit distinct patterns in loan outcomes. ▪ Missed repayments : This implies that customers who have a higher number of missed repayments are likely to face larger losses in the event of default. It suggests that a history of missed repayments may indicate a higher level of credit risk and a greater likelihood of experiencing significant losses. 
▪ Tenure years : The model suggests that the loss given default risk is lesser for the loans with higher tenure. The loans with lower tenure are more likely to be default. 
▪ Repayment total : The higher the repayments are done, the lesser is the loss given default. By considering the impact of each feature, the model can help identify customers with the loss given default value. This will help the business to make more informed decisions related to risk management and mitigation strategies.
# Recommendations:
###### Customer Segmentation : The business can use the features to segment customers based on their risk profile. This segmentation can help tailor risk mitigation measures. 
###### Risk Assessment : Assign appropriate risk levels based on factors such as vintage_in_months, number of loans and missed repayments. This can help manage the risk-reward tradeoff and optimize profitability while minimizing potential losses. 
###### Early Warning System : Monitors key features such as missed repayments and number of loans to identify customers likely to default and offer them financial counseling or restructuring options. This approach can help reduce the likelihood of default and mitigate potential losses. 
###### Customer Retention : Offer incentives, loyalty programs, or personalized services to encourage long term relationships with the bank. The long tenure is likely to reduce the default risk. 
###### Proactive measures : Revise collateral requirements or loan terms for customers with higher risk profiles, such as those with a higher number of loans or missed repayments
