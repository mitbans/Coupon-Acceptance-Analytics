# Will a Customer Accept the Coupon?
UC Berkeley, PC-MLAI, Practical Application 1

## Summary of Findings

### Introduction
This repository contains the code and analysis for "On route coupon acceptance while driving". The project aimed to distinguish between customers who accepted a driving coupon versus those that did not.

### Data
This data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

### Methodology
Overview of the methodologies, techniques, and algorithms used for analysis:
- Exploratory Data Analysis (EDA)
- Statistical summary</li>
- Data Visualization using Matplotlib, Seaborn and Plotly libraries

### Results
Key findings and insights from the analysis.

- Acceptance rates for Bar Coupons:
  - Higher for people:
    - between the age 25 to 30
    - who go to the bar more than once a month,its highest for those who go to the bar more than 3 times
    - who had passengers that were not a kid
    - had occupations other than farming, fishing, or forestry
    - were not widowed
  - Lower for those who go to cheap restaurants more than 4 times and income is less than 50K</li>

- Acceptance rates for Coffe House Coupons:
  - Acceptance rates are higher for:
    -	For drivers who went more than once
    -	Female travelling with friends
    -	Single, unemployed or student, age 21-30
    -	income less than $62K and coupon expiration 1d
    -	People who have no urgent destination
    -	time at 10 am and 2 pm
    -	temepratures at 80 degrees
  -	weather doesn't seem to affect the acceptance rates but the footprint increases on a sunny day
  -	Acceptance rate is reducing as the distance increases, is higher for distances between 5-15 min
  -	coupons were provided more frequently in the opposite direction but acceptance rates are higher in the same direction        
       
### Conclusion
- It will be beneficial to send Bar and Coffee House coupons to respective customer segments as listed in key findings
- Currently more coupons are sent in the opposite direction which has lower acceptance rates, generate more coupons in the same directions

<h3>Future Work</h3>
<p>Exploring other types of coupons</p>

<h3>Repository Structure</h3>
<ul>
  <li><code>data/</code>: Contains dataset used in the analysis.</li>
  <li><code>notebooks/on_route_coupon_acceptance_recommendation.jpynb</code>: Jupyter notebook with code for data analysis.</li>
  <li><code>README.md</code>: Summary of findings and link to notebook</li>
</ul>

<h2>Notebook</h2>
<p>The detailed analysis and code can be found in the Jupyter notebook <a href="https://github.com/mitbans/coupon-acceptance-analytics/blob/main/notebooks/on_route_coupon_acceptance_recommendation.ipynb">here</a>.</p>
