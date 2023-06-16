# Credit-Card-Fraud-Detection

Basically dataset is taken from Kaggel containing the transactions made by credit cards in September 2013 by european cardholders.As always most of the time finance data is Imbalanced. So performed Oversampling to overcome the Imbalance dataset with the help of the SMOTE technique,after that performed EDA to get some insight of the data for which I have used matplotlib library.To get the correlation between the variables in the dataset and finding which is important for the dependent varaible , I have use Correlation matrix.

Then comes the Data Modelling part where I have choosen the Isolation Forest algorithm which is good in Anomly detection.
The algorithm is based on the fact that anomalies are data points that are few and different. As a result of these properties, anomalies are susceptible to a mechanism called isolation.
