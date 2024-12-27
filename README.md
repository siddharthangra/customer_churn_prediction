# **Credit Card Customer Churn Prediction Model**

1. This binary classification model aims to predict which users will exit the credit card service, achieving an accuracy of 82%, enabling informed business decisions.
2. The model employs a Sequential Neural Network architecture with two hidden layers, utilizing the ReLU activation function for enhanced prediction accuracy and model tuning.
3. A threshold of **0.275** was determined using Youden's statistic and visualized on the ROC curve. Predictions with probabilities exceeding this optimal threshold are classified as 1, while others are classified as 0.
4. This threshold, although it decreases the model's accuracy from 85% to 83%, is necessary for better recall and specificity. Recall and specificity address the model's tendency to predict false positives or false negatives. Tackling these tendencies is crucial, as it can be costly if false negatives increase. This could lead to uninformed decisions and ultimately result in losing customers by failing to identify those at risk of exiting services.
