# Credit-Card-Churn
Predicting Credit Card Churn: A Data-Driven Approach 

Introduction
Banks are concerned about customer attrition, particularly among credit card users. At Thera Bank, credit card services provide significant revenue through various fees. However, The Bank has recently experienced a decline in credit card users, prompting an in-depth analysis of customer behavior to understand the reasons behind this trend. With data science, we aim to build a model to identify customers likely to discontinue their credit cards, allowing Thera Bank to improve retention strategies and enhance customer satisfaction.
Objective
The primary goal is to develop a classification model predicting whether customers will stop using their credit cards. By identifying key factors driving customer attrition, The Bank can take action to retain these customers and prevent potential revenue loss.
Data Overview
The  Bank's dataset includes detailed information on customer demographics, credit card usage patterns, and account history. Here are some of the key features used in our analysis:
Client Demographics: Includes age, gender, marital status, education level, and income category.
Credit Card Account Details: These include attributes such as credit limit, revolving balance, average open-to-buy, and utilization ratio.
Activity Indicators: Total transactions, transaction amounts, inactivity periods, and contact counts within the last 12 months.

Key metrics, such as the average utilization ratio (indicating how much of the credit limit is used on average), help paint a picture of the customers' financial behavior, often indicative of churn.
Exploratory Data Analysis (EDA)
My exploratory analysis focused on understanding customer demographics and credit card activity patterns. Key insights included:
Demographic Influence: Factors such as age, education level, and income category provided initial indications of segments more prone to attrition.
Credit Usage Patterns: The average utilization ratio and revolving balance were critical indicators. Customers who maximized their credit limit or consistently had a high revolving balance showed unique patterns.
Activity and Inactivity Trends: Months inactive in the last 12 months and contact frequency with the bank were insightful predictors, suggesting that low engagement or excessive inactivity might correlate with a higher likelihood of leaving.

This exploratory phase helped me refine the  feature selection for building the classification model.
Model Development
I  implemented various classification models for the prediction task and evaluated them based on accuracy, precision, recall, and F1 score. Here's a breakdown of the modeling process:
Data Preparation:
Features were preprocessed by handling missing values and encoding categorical variables.
I used feature scaling to ensure standardized numerical features, improving model performance.
Model Selection and Training:
Multiple models were tested, including Logistic Regression, Decision Trees, Random Forests, and gradient-boosting classifiers.
Cross-validation techniques were applied to mitigate overfitting and ensure generalizability.
Evaluation:
Among the models, Gradient Boosting and Random Forest showed the highest predictive accuracy.
The F1 Score was particularly important, balancing precision and recall to ensure that true positives (correctly identified attrition cases) were maximized without over-predicting attrition.
Maximized without over-predicting attrition.

Key Model Insights
Gradient Boosting proved to be the most effective model in predicting credit card churn. By analyzing feature importance, we found that:
Months inactive and Total transaction count were top indicators of churn, suggesting that inactive customers and those with decreasing transactions were at higher risk.
Credit limit and average utilization ratio were also significant, as they highlighted customers with either low usage or credit exhaustion, both of which can signal dissatisfaction or financial constraints.

Implementing Insights for Retention
The model allows The Bank to identify at-risk customers proactively and implement targeted interventions. Some potential actions include:
Engagement Campaigns: Reaching out to inactive customers with exclusive offers or rewards to boost engagement.
Credit Limit Adjustments: Offering personalized credit adjustments for those at their limit to enhance their spending capacity.
Enhanced Customer Support: Increasing touchpoints for high-risk customers to address any concerns about fees or services.

By leveraging these insights, Thera Bank can enhance customer satisfaction, address attrition risk factors, and improve retention.
Conclusion
Using data-driven techniques, we can successfully developed a model that accurately identifies credit card customers at risk of attrition. This model supports Thera Bank in retaining customers and deepens the understanding of behavioral patterns that contribute to customer satisfaction. Thera Bank can continue strengthening its relationship with credit card users through strategic retention efforts and minimizing churn rates.
