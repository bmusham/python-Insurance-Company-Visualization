# python exploratory data analysis & visualization Project

## Introduction

The dataset about Vehicle Insurance policies sold by a company, sourced from the Kaggle website (www.kaggle.com/datasets/lakshmanraj/vehicle-insurance-policy). It shows data about different policy holders along with their vehicle details and policy premium details. Key parameters related to the customer are Date of Birth, Credit Score, Gender Key parameters related to the vehicle are Vehicle Body, Vehicle Age and Vehicle Value Key parameters related to the policy are Policy Number, Number of Claims, Claim Cost, Annual Premium Amount.

In this project, we have drawn different trends around the data set and implemented different data visualizations to represent these trends.

The data consists of the following types of data: 3 integer fields: policy number, vehicle age and number of claims 6 float fields: age category, credit score, traffic index, vehicle value, claim cost and annual premium 2 object fields: gender, area, vehicle body, policy effective date and date of birth are date/timeline fields

The data set contains 60392 rows and 14 columns with 3.11% missing values in total.

The rows/observations are unique as each row contains the field 'Policy Number', which is unique for each row in the data. This field serves as a primary key in case if we want to extract details about a specific policy from the data set.

## Data Visualization

We have taken key parameters from the data set that are important in the context of business of the vehicle insurance company into consideration and inferred key trends around them to help them make key decisions pertaining to their business. The key parameters include: Age of the policy holders, their credit scores, area of residence, traffic index, number of claims made. These parameters are crucial in helping them understand the trends and making decisions We ignored the parameters such as Policy number, policy effective date as they have little significance when it comes to inferring trends by using them.

## Insights

Younger policy holders have lesser credit score and tend to make more claims. On the other hand, Older policy holders have higher credit score and tend to make less claims. Hence, younger customers tend to be more riskier category among the policy holders.

As the vehicle age increases, the vehicle value depreciates and the number of claims made increases. Hence, policy holders with older vehicles tend to use the policy more than the ones with newer vehicles

So, to summarize we can say that:

Younger customers in age groups 20-50 are a riskier category among the policy holders.
Older Customers are less risky compared to the younger ones
Customers with older vehicles have a higher chance to claim the insurance policy

## Recommendations

Based on the above observations, we have the following suggestions for the Vehicle Insurance Company:
The annual premium value is same for all the policies irrespective of the nature of the policy holders and their vehicle parameters. It will be profitable to the company if the premium value is customized based on the above observations.
Categorize the policies based on the nature of the customer, type of vehicle they hold and number of claims they made.
Basic Plan: For customers aged 51-100 with vehicle age in between 0-2 years. Fix the premium value to 500 dollars and categorize them as safe customers
Basic Plus Plan: For customers aged 51-100 with vehicle age in between 2-4 years. Fix the premium value to 1000 dollars and categorize them as risky customers
Advanced Plan: For customers aged 20-50 with vehicle age in between 0-2 years. Fix the premium value to 1500 dollars and categorize them as moderately risky customers
Advanced Plus Plan: For customers aged 20-50 with vehicle age in between 2-4 years. Fix the premium value to 2000 dollars and categorize them as highly risky customers

Hence, we would add two additional rows to the data set to indicate the Insurance Plan and the Customer Category. Also, change the annual premium value according to the customer category and insurance plan. The metrics would look as below:

![image](https://user-images.githubusercontent.com/100491016/213258259-d48144f4-140e-4bbe-9a57-7526266ab784.png)
