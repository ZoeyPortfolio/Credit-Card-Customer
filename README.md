# Credit-Card-Customer
This project is trying to help bank managers to find factors and ways to keep customers.

In this project, I used the Propensity Score Matching and Logistic Regression Model to help bank managers find factors and solutions to prevent their customers from ending their relationships or being attracted by other banks. I focused on exploring the causal inference between credit limit and customer retaining. 

### Step 1 Collect and Clean the data 
The data is obtained from Kaggle with 10127 observations and 23 variables. I selected useful variables from the large dataset and renamed variables. I filtered the unknowns and removed NAs. I created two new binary variables. 

### Step 2 EDA
I conducted an Exploratory Data Analysis to present a brief idea of the dataset. 

### Step 3 Propensity Score Matching
I used Propensity Score Matching because the total number of customers with high credit limits is different from the total number of customers with low credit limits in the observational dataset. The treatment ground and control group sizes are not balanced. Therefore, I used Propensity Score Matching to redistribute the data, because it is unethical to randomly distribute customers into high credit and low credit limits. Through Propensity Score Matching, the treated and controlled observations are matched, and observations not matched are removed from the dataset. 

### Step 4 Logistical Regression Model
I created a logistical regression model to show the casual inference between whether customers stay in credit card service and high credit limit. 

### Step 5 Conclusion
When people have a high credit limit (credit limit is higher than $10,000), they have a larger probability of staying in credit card service. 
