# Social Media Analytics 
The training data from “Influencers in Social Networks” dataset from Kaggle was used to identify key predictors of social influence in Twitter.You can access the dataset from: https://www.kaggle.com/c/predict-who-is-more-influential-in-a-social-network/overview. The dataset has variables like retweets sent, following count, mentions sent, posts etc. for each person based on their Twitter activity. The model with the highest accuracy identified the top 5 predictors of social influence in Twitter.

## Analysis 
1. I first performed data wrangling on ~5k records to remove N/A and missing values. Following which, I found the correlation to better understand the strenght of relationship between the variables. 
2. Using the training set, I created machine learning models in Python. I applied 4 models: Logistic Regression, Random Forest, K-Nearest Neighbours and XGBoost. Among these models,XGBoost gave the highest accuracy of 81% along with highest precision, recall and f-measure of 79%. 
3. The key predictors of social influence according to XGBoost model are: A/B_listed_count, A/B_follower_count, A/B_network_feature_3, A/B_retweets_received and A/B_network_feature_2.
