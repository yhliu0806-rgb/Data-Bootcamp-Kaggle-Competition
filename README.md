# Data-Bootcamp-Kaggle-Competition
My first model I dropped all the columns that had missing models. For my final model, I added the columns back so I could use data on features such as the basement quality and garage finish. I excluded ID and SalePrice from the X values, but otherwise used all the features in the dataset. 

For the final model, the pipeline I used first filled the missing values with the average for the numerical values, and then it filled the categorical values with the most common category. The pipeline than used onehotencoding and ordinal encoding to help convert both nominal and ordinal features into numerical values. I then finally used a linear regression model to fit X_train and y_train, and then used RMSE to measure the strength of the model. 
