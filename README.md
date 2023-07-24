# IBM-HR-Analytics-Employee-Attrition


<img src="https://github.com/Yash-Raghav/IBM-HR-Analytics-Employee-Attrition/assets/82383225/6682f13d-5cdc-4008-a0be-c74c9d18c7e3" width="500" height="500"> 


Problem: Why Workers Quit?


Employees are the backbone of the organization. Organization's performance is heavily based on the quality of the employees. Challenges that an organization has to face due to employee attrition are:

  -	Expense in terms of both money and time to train new employees

  -	Loss of experienced employees

  -	Impact in productivity

  -	Impact to profit

**Aim: To uncover the factors that lead to employee attrition and explore the relations between different variables.**


Insights gathered from the data - 

  -	Attrition rate related to gender is biased a little bit (2%) towards male side but not necessarily indicative of any pattern.
  
  -	Almost 30% of employees doing overtime quit the company compared to 10% of employees who do not do overtime. 
  
  -	Sales and Human resources have a high rate of attrition as per data in department, education field and job role.
  
  -	25% of employees who travel frequently quit, compared to 8% of employees of do not travel at all. 
  
  -	Attrition rate is high among Unmarried employees indicating that employees who are married prefer a job stability and sustained source of income.
  
  -	Most employees who quit are around the age of 30. Older employees prefer to have a stability in jobs.
  
  -	Employees with lower income have a higher rate of attrition.
  
  -	Employees with bachelor’s degree have a higher rate of attrition.
  
  -	Lower environmental, job and relationship satisfaction level among employees is indicative of higher rate of attrition.
  
  -	Lower levels of work life balance and job involvement indicate a higher attrition rate.
  
  -	Employees with lower job level quit more frequently.
  
  -	Years at company, in current role and with current manager indicate that employees tend to quit early in job. The skewness of graphs indicate that older and more experienced employees tend to stay with the company.

While doing predictive modelling , achieved a max f1-score of 87% with precision and recall of 96% and 89% for **class 0** and 40% and 68% for **class 1** using a SVM model. This huge difference is due to the imbalances in classes in the data.

![image](https://github.com/Yash-Raghav/IBM-HR-Analytics-Employee-Attrition/assets/82383225/f3313489-2a71-4b4a-b5f9-40b9b79304ea)

Further data processing using SMOTE oversampling was done to balance the classes and bring down the difference. Final maximum f1-score achieved is 93% with precision and recall of 96% and 90% for **class 0** and 89% and 95% for **class 1**.

![image](https://github.com/Yash-Raghav/IBM-HR-Analytics-Employee-Attrition/assets/82383225/fa735871-1051-48b8-b5db-8636f7b6f8d2)



