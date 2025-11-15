# Gradient_descent-Linear-DT-RF-GB-regression-and-model-evaluation
the repository on regression analysis (gradient descent) on the ecommerce data. the idea is using regression method to see how important a feature is. 

**Project : Understanding Regression Model on Simple approach**.


The objective is to understand regression model approach and compare several method and how the overall interpretation and it translates to business ( given simple dataset). On this data we will check several columns / feature related clients behaviour. The target on the regression is “Yearly spent” . the predictors will be used are :
1.	Avg session 
2.	Time on app
3.	Time on website
4.	Length of membership

<div align="center">
<img width="556" height="448" alt="image" src="https://github.com/user-attachments/assets/22cf66b0-70f9-4d5f-b0e1-1d15753312b7" />
</div>



**Simple Explanatory Data analysis (EDA)**

explore the data. to get better information and to get to know more of our data. get better understanding. These several plots help to visualize overall data condition and general spread. 

<div align="center">
<img width="510" height="471" alt="image" src="https://github.com/user-attachments/assets/12e6e21a-f8f3-4b4a-a15e-8c0f241975aa" />
</div>

<div align="center">
<img width="347" height="257" alt="image" src="https://github.com/user-attachments/assets/13a0d385-6354-4b0b-b825-a5a063144740" />
</div>




**Splitting between Train and Test**
Data splitting is important to build model for data fitting ( train set) , validation ( valid set) and other set ( OOT , OOT2, etc) if necessary. before split data into test and train, we need to choose only the numerical dataset. In general current feature have 4 numerical predictor , and 0 Categorical predictors. Meaning  no additional transformation for categorical required. 

<div align="center">
<img width="381" height="49" alt="image" src="https://github.com/user-attachments/assets/b276a29e-9716-44b8-a7db-57da2deb8c40" />
</div>




**building the training Model**
On this iteration, the model will mainly try and experiment on **Linear model regression**, several additional decision Tree, random forest and gradient boosting as additional benchmark using more advance model. But at the end of the day, interpretability is one of critical points when delivering projects in especially higher level .

<div align="center">
<img width="344" height="290" alt="image" src="https://github.com/user-attachments/assets/793afbd9-a2ed-45c1-9646-dea4f9f9de75" />
</div>





**Model Evaluation**

evaluating model is as important as building model itself. it is necessary to see the performance of the model, how good our model approaches the problem and our data. because of it will be deployed on our data and will be used in real time
calculate the
•	Mean absolute error
•	Root mean square error
•	Root mean absolute error



<div align="center">
<img width="411" height="120" alt="image" src="https://github.com/user-attachments/assets/03935061-a8ec-44a0-be51-6a77c4cfa94a" />
</div>




**plotting the residuals**
from the residuals below we can actually evaluate how our models doing and which model yield better result (observed by the less-wide error distribution)

<div align="center">
<img width="305" height="184" alt="image" src="https://github.com/user-attachments/assets/31f2b890-e3ea-480d-939d-37aa2ecc2ec4" />
</div>



**Result & Interpretation** 

<div align="center">
<img width="172" height="110" alt="image" src="https://github.com/user-attachments/assets/817f4f2b-85c6-4163-944b-a59e2a15f240" />
</div>


how can we interpret the Coefficient of our linear regression model ?
okey, this is how it's done :

- assume, all feature are fixed , increase by 1 on the AVG session length will associaed with an increase of 25.98 total dolars spent.
- assume, all feature are fixed , increase by 1 on the Time on the APP will associaed with an increase of 38.58 total dolars spent.
- assume, all feature are fixed , increase by 1 on the AVG session length will associaed with an increase of 0.19 total dolars spent.
- assume, all feature are fixed , increase by 1 on the AVG session length will associaed with an increase of 61.27 total dolars spent.


the result above shows which feature or stuff they need to focus on more. it is like feature importance on the classification project






