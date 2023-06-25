# Applications-identity-Fraud-Project
This project investigates application identity fraud. This dataset is about Application Identity Theft Data. The data is about credit card applications spanning from January 1, 2017 to December 31, 2017. There are 10 fields with 1,000,000 records. We can achieve a fraud detection rate at 3% of 0.529, 0.525, and 0.507 for training, testing, and out of time, respectively. That means that our model is able to capture 50.7% of all the fraud in the top 3%. This means that our model allows us to reject only 3% of the applications and catch 50.7% of the fraud in those rejected applications. As mentioned previously, our final model choice here is a boosted tree, particularly using the xgboost architecture. In terms of hyperparameters set, we used 20 estimators and set our max depth to 6.