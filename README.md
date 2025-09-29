# Amazon_Coupons
# PROJECT SUMMARY
This analysis was prepared as a practical assignment for an AI/ML class using Python.
The focus of the analysis is to review coupon acceptance rates from an Amazon survey considering their demographic information as well as specific drinking, eating habits.

The Jupyter notebook is here: https://github.com/ZundryPadra/Amazon_Coupons/blob/main/assignment5_1_final.ipynb

# DATA
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:
     
    “Right away”
    
    “Later, before the coupon expires”
    
    “No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).
The CSV data file is here: https://github.com/ZundryPadra/Amazon_Coupons/tree/main/data

# ANALYSIS 
The data review was executed as follows:
1) Cleaning of the data: removing duplicates, identifying missing values, checking for structural issues.
2) Reviewing values of critical features and distribution of coupons accepted by category.
3) The assigment then focus on reviewing "Bar" coupon acceptance considering different parameters like age, how often they normally go to bars, if they are driving alone, etc.
4) Additionally a similar review is also done for the "Coffee House" coupons.
5) Reviews include coupon acceptance proportions and relevant visualizations.

# RESULTS
In general the data review showed an important relationship between Bar and Coffee House acceptance levels for the drivers who visit these establishments (respectivel) 3 or more times per month. As expected, age also has a big impact on the acceptance of Bar coupons. 

