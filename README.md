# Understanding-and-Predicting-Property-Maintenance-Fines
### This project is based on a data challenge from the Michigan Data Science Team (MDST).
This project solves one of the most pressing problems facing Detroit - blight. Blight violations are issued by the city to individuals who allow their properties to remain in a deteriorated condition. Every year, the city of Detroit issues millions of dollars in fines to residents and every year, many of these fines remain unpaid. Enforcing unpaid blight fines is a costly and tedious process, so the city wants to know: how can we increase blight ticket compliance? 
The first step in answering this question is understanding when and why a resident might fail to comply with a blight ticket. This is where predictive modeling comes in. The task is to predict whether a given blight ticket will be paid on time.
The train.csv model contains data for training the model. 
We use data from test.csv to predict the probablity that each corresponding ticket from test.csv will be paid.
### Approach 1
We compare sklearn.ensemble.RandomForestClassifier and sklearn.ensemble.GradientBoostClasifier to predict the probablity
