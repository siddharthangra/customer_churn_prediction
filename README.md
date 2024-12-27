# **Credit Card Customer Churn Prediction Model**

1.  Based upon the Credit card dataset of users, Model Aims to predict which user will exit the credit card service with accuracy of 81 percent, so that informed business decision can be taken accordingly.
2. Model is based on Sequential Neural network model with 2 hidden layers, using relu as activation function for better predictions and tuning.
3. Threshold of ** 0.275 ** is chosen using Youden's stattistic and Visualising it on ROC curve i.e prediction with probabilities higher than this optimal threshold is taken as 1 and other as 0.
4. This threshold even though, decreases the accuracy of model by 3 percent is necessary for better recall and specificity of the model, which is the tendency of model to predict fake positive or fake negatives; tackling which is necessary as it can cost heavy if fake negative increases leading to uninformed decision to tackle customer exiting the services.
   
