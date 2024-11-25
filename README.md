# Walmart-Confidence-Interval-CLT
### Walmart- Confidence Interval &amp; CLT

### About Walmart
- Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores in the United States.
- Walmart has more than 100 million customers worldwide.

### Business Problem
- The Management team at Walmart Inc. wants to analyze the customer purchase behavior (precisely, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions.
- They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men?

### Dataset
- The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. 
- Dataset link: Walmart_data.csv
- The dataset has the following features:
  - User_ID:	User ID
  - Product_ID:	Product ID
  - Gender:	Sex of User
  - Age:	Age in bins
  - Occupation:	Occupation(Masked)
  - City_Category:	Category of the City (A,B,C)
  - StayInCurrentCityYears:	Number of years stay in current city
  - Marital_Status:	Marital Status
  - ProductCategory:	Product Category (Masked)
  - Purchase:	Purchase Amount

### Approach
- Importing the dataset and doing usual data analysis steps like checking the structure & characteristics of the dataset.
- Detecting Null values & Outliers (using boxplot, “describe” method by checking the difference between mean and median, isnull etc.)
- Doing some data exploration steps like:
  - Tracking the amount spent per transaction of all the 50 million female customers, and all the 50 million male customers, calculating the average, and concluding the results.
  - Inferencing after computing the average female and male expenses.
  - Using the sample average to find out an interval within which the population average will lie.
  - Using the sample of female customers you will calculate the interval within which the average spending of 50 million male and female customers may lie.
- Using the Central limit theorem to compute the interval.
- Changing the sample size to observe the distribution of the mean of the expenses by female and male customers.
- Concluding the results and checking if the confidence intervals of average male and female spends are overlapping or not overlapping. How can Walmart leverage this conclusion to make changes or improvements?
- Performing the same activity for Married vs Unmarried and Age. For Age, we can try bins based on life stages: 0-17, 18-25, 26-35, 36-50, 51+ years.
- Finally giving insights and recommendations and action items to Walmart.





