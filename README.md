# A/B Testing Online Advertising
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

A major company with a large user base is exploring the potential of increasing sales by displaying ads on its website. However, they are uncertain whether these ads effectively drive sales growth. To make data-driven decisions, the company wants to conduct an **A/B test**, a proven method for evaluating the impact of changes by comparing two groups: a control group and a treatment group.

In this experiment, the primary metric being tested is the **conversion rate**, which measures the percentage of users who made a purchase.

The A/B test was conducted over a 30-day period with 20,000 customers:

* The **treatment group** (labeled "ad") consists of customers exposed to ads.
* The **control group** (labeled "psa") includes those who were not shown any ads.

## Hypothesis Tests Conducted:

* **Two-Tailed Test:** This test was used to check if there was any significant difference in conversion rates (higher or lower) between the two groups.
* **One-Tailed Test:** This test specifically checked if the treatment group had a higher conversion rate compared to the control group, assuming that the ads could only have a positive effect on sales.

#### Power and Significance:

* The **statistical power** of the test was set to 0.80.
* The **significance level** ($\alpha$) was set to 0.05.


## Dataset:

**Variables**: 
 
* **customerID**: Unique identifier for the customer.
* **test group**: A categorical variable in an A/B testing setup.
'ad' indicates customers exposed to ads (treatment group), and 'psa' represents those not exposed (control group).
* **made_purchase**: A Boolean value representing whether or not the user made a purchase after seeing an advertisement.
* **days_with_most_add**: A day of the month when the user saw the most ads.
* **peak ad hours**: An hour of the day when the user saw the most ads.
* **ad_count**: Total number of ads seen by each user.

      
You can access the dataset here: [Online Advertising Effectiveness](https://www.kaggle.com/datasets/farhadzeynalli/online-advertising-effectiveness-study-ab-testing/data)

## Findings:
Main result is:

 * Ads lead to an increase in sales. 
 
Additional findings include:

* The treatment group exhibits higher customer activity and a greater total number of ads viewed compared to the control group.
* Between 15:00 and 23:00, customer activity and the number of ads seen are significantly higher than during other hours.
* Despite the increased activity during these hours, the peak times for making purchases across all users are at midnight (0:00), 5 AM, and 7 AM. This indicates that higher customer activity does not necessarily lead to higher conversions.

