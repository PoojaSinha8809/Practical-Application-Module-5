# Practical-Application-Module-5
This repository contains files related to ML and AI professional training program Practical Application Module 5

The repository ccvers the problem statement related to "Will The Customer Accept the Coupon?"

This project contains a Jupyter Notebook that contains the analysis using panda and vsisulaization to find the condition when Customer will accept the Coupon.

# Findings and Extension
In the inital investigation, different coupon group options was explored. To start the analysis first I read the data.csv as dataframe and then work on finding the missing and duplicate records. 

In the analysis it was found that the missing and duplicate records are very less compared to total records. So I removed the rows with missing values and duplicate data. 

Then the focus was to filter the data for Bar Coupon and based on the analysis and investigation done on "Bar" Coupon the overall acceptance proportion on Bar Coupon was found. In the anyalsis it is noticed  is acceptance proportion and  rejected proportion.

It is observed that driver who visited bar more than once in a month, with no kid as passenger, occupation other than farming, fishing and forestry and above age 25 has most desirable chance to accept the bar coupon. Althought the acceptance rate for Bar Coupon in that condition is 7.63% of total count of Bar Coupon available. It is also observed that the driver who visited Bar less than once in a month, had Kid as passenger, unemployed and below age 25 is also desirable condition with 1.72% rejectation rate to reject the Bar Coupon. 

It is noticed that the data did not fullfill the desire condition that has impact on acceptance and rejection rate for bar coupon. 

# Extended Investigation and Findings
In the further investigation on "Coffee House" coupon, It is observed that driver who visited coffee house more than once in a month, with no snowy weather, and above age 21 has most desirable chance to accept the coffee House Coupon. In this case the acceptance rate for Coffee House coupon is 28.2% of total count of Coffee House available. It is also noticed that driver who visited coffee house less thans once, weather is Snowy,and  below age 21 has most desirable condition to reject the coupon. In this case rejection rate is 33.6%

It is noticed that the data needs improvement to full fill the desire condition to accept the coupon. Looking at acceptane and rejection rate for most desirable condition to accept anmd reject the coffee house coupon together covers 61.8% of the total data which means that approx 38.1% of data needs improvement to fit in correct in correct category. 

The Jupyter Notebook with details on investigation and findings can be find  here: https://github.com/PoojaSinha8809/Practical-Application-Module-5/blob/main/prompt.ipynb

# Action Ttem and Recommendation 
The next action step is to analyze the data identify the customer acceptance criteria for other group of coupon to find the condition when Coupon was accepted and rejected by Driver. 
Also we need to improve the data so that rejection rate and acceptance rate total covers the total data for the group of coupon. Once we improve the data we have better visualize for acceptance and rejection rate on total data. 
