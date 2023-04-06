# SageMaker Multiple Linear Regression: Predict Stock Market Price

Jupyter Notebook that uses SageMaker Linear Learner to train a multiple linear regression machine learning model. The model loads an S&P 500 Stocks dataset and uses Employment statistics and Interest Rates to predict the Stock index Price.

1. Load dataset and perform Exploratory Data Analysis (EDA)
2. Split the dataset into training and test data
3. Upload the training data to S3
4. Train linear regression model
5. Deploy trained model as endpoint
6. Cleanup - Delete the endpoint