# Bank Churn Prediction Using Machine Learning
This project was the final project of the Digital Skill Fair 32.0 Data Science event held by Dibimbing ID. It analyzes customer churn in a banking context using machine learning techniques.

### Background
In the highly competitive banking industry, the challenge of customer retention has become increasingly critical, as losing customers directly impacts sustainable growth and profitability.

### Goals
To develop a predictive model to identify customers likely to churn.

### Methodology
1. Data Collection
   Data was collected from [Kaggle](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn/data) named "Bank Customer Churn". There are 10.000 rows of data and 18 features about bank customer churn.
2. Data Pre-Processing
   The data is clean enough to process to the next analysis step
3. Exploratory Data Analysis
   Conduct a comprehensive analysis to extract valuable insights from the data. It helps to identify relationships between variables, discover patterns and trends, guide model selection, and inform data cleaning processes for more effective analysis.
4. Feature Engineering
   Create or modify the feature of data  to improve model performance. In this project, we performed one-hot encoding to convert categorical data into a numerical format suitable for machine learning algorithms, and applied feature scaling to improve the performance and convergence of these algorithms, particularly those sensitive to data scale, such as gradient descent-based methods.
5. Data Modelling & Evaluation
   We built a bank churn prediction model by comparing two algorithms: Random Forest Classifier and Gradient Boosting Classifier. The performance of each model was evaluated using a confusion matrix and key evaluation metrics, including accuracy and F1 score.

### Conclusion
In this notebook, we conducted an analysis and built a predictive model for customer churn in a bank, using a dataset that includes a range of customer attributes. Throughout the analysis, we gained valuable insights into the key factors influencing customer churn and developed a machine learning model to make predictions.

Our exploratory data analysis highlighted several important observations.We observed that factors such as age, geography, and the frequency of complaints had a significant impact on customer churn. Additionally, we noted that variables like balance, the number of products held, and active membership status showed weaker correlations with churn but may still provide valuable insights when considered alongside other factors.

Using machine learning techniques, we developed predictive models for customer churn by comparing two algorithms: Random Forest and Gradient Boosting Classifier. Through hyperparameter tuning, we optimized each model and evaluated their performance using metrics such as accuracy, precision, recall, and F1 score. The results showed a slight difference in performance between the two models, with Random Forest emerging as the best-performing model overall.

### Recommendations
**1. Target High-Risk Customers:** Utilize the insights gained from the analysis to identify customers at high risk of churning based on key factors such as age, geography, and complaint frequency. Implement targeted retention strategies for these segments, including personalized communication and outreach. For example, consider creating specific campaigns that address common concerns or needs relevant to these demographics, thereby fostering a stronger relationship with at-risk customers.

**2. Enhance Customer Support:** Focus on improving customer support services to reduce the frequency of complaints, a significant predictor of churn. Invest in training staff to handle issues more effectively and increase the responsiveness of support channels. Implement a proactive approach by reaching out to customers who have previously filed complaints to ensure their concerns have been resolved, and provide follow-up support to enhance their experience and satisfaction.

**3. Offer Personalized Incentives:** Leverage the predictive model to craft personalized offers or incentives for customers identified as at risk of churning. This could include discounts on fees, loyalty rewards, or exclusive promotions tailored to their preferences and banking behavior. By making customers feel valued and appreciated, the bank can encourage them to remain engaged and reduce the likelihood of churn.
