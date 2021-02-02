# Stock Market Prediction

~10,000 rows of financial data on stocks from 15+ GICS sectors were collated. Historical data on stocks traded on the S&P500 was used to define the target variable "Outperformance". During the 2016-2019 period, the S&P500 index saw price appreciation of of 43.88%. The outperformance benchmark was set at 3% above the index; therefore, a stock  showing a price appreciation of 46.88% or more over 3 years would meet the outperformance criteria.

Data cleaning was performed before 3 models were trained on the dataset on SPSS: decision tree (C5.0 classifier), neural net and Bayesian network. Ensemble methods, bootstrapping and splits (particularly on sector) were used to produce multiple iterations of each algorithm to determine the most appropriate model for this analysis. The final models were selected based on overall accuracy and relative accuracy among split groups. 




![image](https://user-images.githubusercontent.com/78432605/106653930-6ffebd80-6565-11eb-8994-b8e874e14176.png)
![image](https://user-images.githubusercontent.com/78432605/106653116-60cb4000-6564-11eb-831d-aa4ac8dd189f.png)


**Decision Tree (C5.0)**

![image](https://user-images.githubusercontent.com/78432605/106653609-09799f80-6565-11eb-88d8-c04bcad8944c.png)
![image](https://user-images.githubusercontent.com/78432605/106653765-3fb71f00-6565-11eb-8873-c8a600ef5c1f.png)
![image](https://user-images.githubusercontent.com/78432605/106653124-63c63080-6564-11eb-92a6-2558d619fbd8.png)


**Neural Net**

![image](https://user-images.githubusercontent.com/78432605/106653496-dd5e1e80-6564-11eb-8d68-5b5ef156c1a1.png)
![image](https://user-images.githubusercontent.com/78432605/106653529-ed75fe00-6564-11eb-80f1-6b9711eaffab.png)
![image](https://user-images.githubusercontent.com/78432605/106653131-66288a80-6564-11eb-993a-56e73c67c797.png)
![image](https://user-images.githubusercontent.com/78432605/106653162-6e80c580-6564-11eb-8fed-3dc3a061b8db.png)
![image](https://user-images.githubusercontent.com/78432605/106653172-704a8900-6564-11eb-990a-34b4af67acde.png)



**Bayesian Network**

![image](https://user-images.githubusercontent.com/78432605/106653548-f23ab200-6564-11eb-9c33-1fa0c5922cc1.png)
![image](https://user-images.githubusercontent.com/78432605/106653179-73457980-6564-11eb-9b89-a11ab5c25f67.png)
![image](https://user-images.githubusercontent.com/78432605/106653183-7476a680-6564-11eb-8688-2eeb889db94d.png)
![image](https://user-images.githubusercontent.com/78432605/106653187-76d90080-6564-11eb-9361-1ea11db37d97.png)

