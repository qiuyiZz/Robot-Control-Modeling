# Robot-Control-Modeling
## Dataset
A modified version of a real-life dataset. The modified dataset describes a control problem, namely the task of controlling a robot. There are 40 features (continuous) that describe the status of the robot, and the target value (continuous) describes the appropriate action corresponding to the feature. The training dataset has 8250 samples. 

The project is comprised of three milestones and a final report. 
- In Milestone 1, I conducted basic data exploration and compare a few baseline models(Linear Regression, k-Nearest Neighbors, Gaussian Process, Neural Network, Random Forest Regressor, Gradient Boosting Regressor). 
- In Milestone 2, I performed data preprocessing and feature engineering(feature selection, Clustering, and PCA) to improve model performance. 
- In Milestone 3, I chose the Gaussian Process Regressor model and tune its hyperparameters using Grid Search to successfully train my own machine learning model and compete with other students in a classroom Kaggle competition. The obtained RMSE on the test dataset is 0.16856
