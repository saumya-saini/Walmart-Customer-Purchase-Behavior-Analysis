# Walmart Customer Purchase Behavior Analysis

##  Overview

Analyzed Walmart customer transaction data to understand purchase behavior, evaluate spending differences across demographics, and generate data-driven business insights using statistical methods like Confidence Intervals (CI) and the Central Limit Theorem (CLT).


##  Dataset

The dataset includes customer attributes such as:

* User_ID,
* Product_ID
* Gender
* Age
* Occupation
* City_Category
* Stay_In_Current_City_Years
* Marital_Status
* Product_Category
* Purchase (transaction amount)


##  Objective

* Analyze customer spending behavior across demographics
* Determine if men and women spend differently
* Apply Confidence Intervals and CLT to generalize findings to the population
* Identify key factors influencing purchase amount


##  Key Analysis

* Exploratory Data Analysis (EDA)
* Univariate & Bivariate Analysis
* Confidence Interval Estimation
* Central Limit Theorem (CLT) Validation


##  Key Insights

* Male customers spend more per transaction than female customers, and this difference is statistically significant.
* Age and marital status do not significantly impact spending behavior, as confidence intervals overlap.
* Purchase distribution is right-skewed, with most transactions being low-value and a few high-value outliers.
* Product category has the strongest influence on purchase amount, showing clear variation across categories.
* Other demographic factors like city have some impact on spending
* Stay duration have minimal impact on spending.


##  Customer Segments

* High Spenders: Customers purchasing high-value product categories
* Typical Buyers: Majority of customers making moderate-value purchases
* Occasional High-Value Buyers: Customers responsible for outlier transactions


##  Tools Used

* Python (Pandas, NumPy)
* Matplotlib, Seaborn


##  Business Impact

* Helps design targeted marketing strategies based on gender
* Identifies high-revenue product categories
* Enables data-driven decision making using statistical validation

Supports better inventory and promotion planning
