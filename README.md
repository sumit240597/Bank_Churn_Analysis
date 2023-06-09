# Bank_Churn_Analysis

About dataset :- 

RowNumber—corresponds to the record (row) number and has no effect on the output. 
CustomerId—contains random values and has no effect on customer leaving the bank. 
Surname—the surname of a customer has no impact on their decision to leave the bank. 
CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank. 
Geography—a customer’s location can affect their decision to leave the bank. 
Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank. 
Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones. 
Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank. 
Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances. NumOfProducts—refers to the number of products that a customer has purchased through the bank. 
HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank. 
IsActiveMember—active customers are less likely to leave the bank. 
EstimatedSalary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries. 
Exited—whether or not the customer left the bank. 
Complain—customer has complaint or not. 
Satisfaction Score—Score provided by the customer for their complaint resolution. 
Card Type—type of card hold by the customer. Points Earned—the points earned by the customer for using credit card.

Steps :-
1.Data preparation- Cleaning, formatting and reshaping the data.
2.Data Modeling- Create quarries to model the data for visualization.
3.Dax Analysis- Create Dax measure for better insights.
4.Data Visualization


Key insights:-
-With the help of DAX create a age group to understand which group of age . 21-40 age group having most numbers of customers i.e. 6.3k and 41-60 age group having high number of exit customers 39.65%.
-According to the customers exits data 899 are males and 1139 are females.
-With the help of DAX function created Account balance group, according to the account balance group customers who had balance between 1-10k their exit % is 100%
-According to the account balance 4765 customers have amount between 100k-200k and 3617 customers have 0 amounts in their account
-According to the data 70% persons have credit card out of that 4k are male and 3k are female.
-Create Credit Score group by DAX function, according to that maximum number customers fall in 601-800 credit score i.e. 6.3k customers , only 645 customers have 801above credit score with 11 years of Tenure and only 19 customers have 201-400 credit score with 10 years of tenure.
-Create Point Group by Dax function, according to that most of the customers i.e. 3.2k have earned point between 501-750 and 751-1000.
