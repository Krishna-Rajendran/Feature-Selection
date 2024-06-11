# Feature-Selection

A significant feature of feature selection is that it analyses a dataset and removes redundant/irrelevant features from it and makes it easier to interpret. The relevant features are then separated into subsets and used for the machine learning model construction. A well-chosen subset will facilitate faster training, increase in accuracy, and reduce the likelihood of overfitting. 

1. Filter Method: It filters the features based on their common characteristics. It is 
desirable when the dataset is huge. 
 
2. Wrapper Method: It uses a predictive model, and the features are wrapped around them. 
This method provides good performance even though they are highly prone to 
overfitting. 

3. Embedded Method: The feature selection process is embedded in the model-building 
phase. This is less prone to overfitting than the wrapper method.  


For this case study, Filter (Variance Threshold), Wrapper methods (Backward and Forward), Embedded method (LassoCV) are used. 
