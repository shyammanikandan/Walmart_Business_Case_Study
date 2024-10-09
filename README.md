# Walmart_Case_Study
Walmart Customer Purchase behaviour analysis


## Objective
The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).
## Important Links
- [Dataset](https://github.com/shyammanikandan/Walmart_Business_Case_Study/blob/main/walmart_data.csv)
- [Jupyter Notebooks](https://github.com/shyammanikandan/Walmart_Business_Case_Study/blob/main/walmart_Casestudy.ipynb)
- [Project Report](https://github.com/shyammanikandan/Walmart_Business_Case_Study/blob/main/Final%20Report.pdf)
## About Data
The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. 

**Product Portfolio**

- The KP281 is an entry-level treadmill that sells for USD 1,500.

- The KP481 is for mid-level runners that sell for USD 1,750.

- The KP781 treadmill is having advanced features that sell for USD 2,500.

### Dataset features
| Feature                      | Description |
| -----------                  | ----------- |
| User_ID	| User ID|
|Product_ID|	 	Product ID |
|Gender|	 	Sex of User|
|Age	|Age in bins|
|Occupation	| 	Occupation(Masked)|
|City_Category	|Category of the City (A,B,C)|
|StayInCurrentCityYears|Number of years stay in current city|
|Marital_Status	| 	Marital Status|
|ProductCategory	|Product Category (Masked)|
|Purchase	|	Purchase Amount|

## Concepts

- Descriptive Statistics
- Data Visualization using Matplotlib and Seaborn
- Correlation
- Probability
- Central Limit Theorem
- Confidence Intervals
- Gaussian Distribution

## Insights

- Confidence Interval of the Purchase Amounts of Male Customer Purchases :
  - 90% Confidence : [9151.93 to 9712.94]
  - 95% Confidence : [9098.19 to 9766.69]
  - 99% Confidence : [8993.16 to 9871.71]
- Confidence Interval of the Purchase Amounts of Female Customer Purchases :
  - 90% Confidence : [8480.45 to 9000.94]
  - 95% Confidence : [8430.59 to 9050.80]
  - 99% Confidence : [8333.15 to 9148.24]
- Average Transaction Value from a Married Customer : 9261 and Unmarried Customer : 9266
- Male Customer transactions are more when compared to female transaction on black friday sale.

## Recommendations

- The Company Should strategise to reduce the difference in the transaction amounts between Male and Female transactions.
- Company Should Target Age group 26 to 45 as they contribute heavily in the day transactions on Black Friday.
- The Company should focus on other parameters like gender, Age.
- Product Categories attracting specific age group can be increased during black friday Sale.


