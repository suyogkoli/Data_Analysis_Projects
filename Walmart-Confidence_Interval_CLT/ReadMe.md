About Walmart

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.


Business Problem

The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).


Dataset

The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. The dataset has the following features:
Dataset link: Walmart_data.csv

User_ID:	User ID

Product_ID:	Product ID

Gender:	Sex of User

Age:	Age in bins

Occupation:	Occupation(Masked)

City_Category:	Category of the City (A,B,C)

StayInCurrentCityYears:	Number of years stay in current city

Marital_Status:	Marital Status

ProductCategory:	Product Category (Masked)

Purchase:	Purchase Amount

1. Import the dataset and do usual data analysis steps like checking the structure &
characteristics of the dataset
  a. The data type of all columns in the “customers” table.
  b. You can find the number of rows and columns given in the dataset
  c. Check for the missing values and find the number of missing values in each
  column

_____________________________________________________________________________________
2. Detect Null values and outliers
  a. Find the outliers for every continuous variable in the dataset
  b. Remove/clip the data between the 5 percentile and 95 percentile
_____________________________________________________________________________________

3. Data Exploration
  a. What products are different age groups buying?
  b. Is there a relationship between age, marital status, and the amount spent?
  c. Are there preferred product categories for different genders?

_____________________________________________________________________________________
4. How does gender affect the amount spent?
  a. From the above calculated CLT answer the following questions.
    i. Is the confidence interval computed using the entire dataset wider for
    one of the genders? Why is this the case?
    ii. How is the width of the confidence interval affected by the sample size?
    iii. Do the confidence intervals for different sample sizes overlap?
    iv. How does the sample size affect the shape of the distributions of the
    means?

_____________________________________________________________________________________
5. How does Marital_Status affect the amount spent?
  a. From the above calculated CLT answer the following questions.
    i. Is the confidence interval computed using the entire dataset wider for
    one of the genders? Why is this the case?
    ii. How is the width of the confidence interval affected by the sample size?
    iii. Do the confidence intervals for different sample sizes overlap?
    iv. How does the sample size affect the shape of the distributions of the
    means?

_____________________________________________________________________________________
6. How does Age affect the amount spent?

a. From the above calculated CLT answer the following questions.
  i. Is the confidence interval computed using the entire dataset wider for
  one of the genders? Why is this the case?
  ii. How is the width of the confidence interval affected by the sample size?
  iii. Do the confidence intervals for different sample sizes overlap?
  iv. How does the sample size affect the shape of the distributions of the
  means?

_____________________________________________________________________________________
7. Create a report
  a. Report whether the confidence intervals for the average amount spent by males
    and females (computed using all the data) overlap. How can Walmart leverage
    this conclusion to make changes or improvements?
  b. Report whether the confidence intervals for the average amount spent by
    married and unmarried (computed using all the data) overlap. How can Walmart
    leverage this conclusion to make changes or improvements?
  c. Report whether the confidence intervals for the average amount spent by
    different age groups (computed using all the data) overlap. How can Walmart
    leverage this conclusion to make changes or improvements?
