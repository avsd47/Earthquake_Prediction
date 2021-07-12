# Earthquake_Prediction
   Machine Learning model to expect whether an earthquake is going to happen.
Tested with various algorithms like logistic regression,random forest and XGBOOST algorithms.
Finally, applied MRMR algorithm for feature selection and supplied selected features as input to XGBoost algorithm, achieved an accuracy score of 97%.

   Dataset obtained for all the three regions namely Chile, Hindukush and California is divided into training and testing sets. For training and validation purposes, 70% of the 
dataset is selected, while testing is performed on rest of 30% hold out dataset. The reason for separate training is that every region 
has different properties and can be classified tectonically into different categories, such as thrusting tectonics, strike-slip tectonics 
and so forth. Therefore every type of region possesses different behaviors and relations to the earthquakes. Thus separate training 
for every region is meant to learn and model the relationship between seismic features and earthquakes for that particular region. 
The proposed methodology includes the use of two step feature selection process. The features are selected after performing 
relevancy and redundancy checks, to make sure that only useful features are employed for earthquake prediction. The selected 
sets of features are then passed to XGBoost Classifier. We have used XGBoost since it uses a more regularized model 
formalization to control over-fitting, which gives it better performance. 

