# Churn-Prediction

# Problem Statement: Customer Churn prediction means knowing which customers are likely to leave or unsubscribe from your service. For many companies, this is an important prediction. This is because acquiring new customers often costs more than retaining existing ones.

# Steps involved in the process:
1. Load Data & Packages for model building & preprocessing
2. Preprocessing & Missing value imputation
3. Select features on the basis of EDA Conclusions & build baseline model
4. Build model using all features & compare with baseline
5. Use Reverse Feature Elimination to find the top features and build model using the top 10 features & compare

# Evaluation metric:
Now, we are looking at the recall value here because a customer falsely marked as churn would not be as bad as a customer who was not detected as a churning customer and appropriate measures were not taken by the bank to stop him/her from churning

# Various Algorithms:
Cross Validation is one of the most important concepts in any type of data modelling. It simply says, try to leave a sample on which you do not train the model and test the model on this sample before finalizing the model.

Reverse Elimination Method or backward selection method to find top 10 features.

Also using various machine learning algorithms to improve the accuracy .

Random Forest classification along with proper Hyper Tunining gives higher recall score.
