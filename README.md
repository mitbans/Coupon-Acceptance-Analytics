<h1>Will a Customer Accept the Coupon?</h1>
<p>UC Berkeley, PC-MLAI, Practical Application 1</p>

<h2>Summary of Findings</h2>

<h3>Introduction</h3>
<p>This repository contains the code and analysis for "On route coupon acceptance while driving". The project aimed to distinguish between customers who accepted a driving coupon versus those that did not.</p>

<h3>Data</h3>
<p>This data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).</p>

<h3>Methodology</h3>
<p>Overview of the methodologies, techniques, and algorithms used for analysis:</p>
<ul>
  <li>Exploratory Data Analysis (EDA)</li>
  <li>Statistical summary</li>
  <li>Data Visualization using Matplotlib, Seaborn and Plotly libraries</li>
</ul>

<h3>Results</h3>
<p>Key findings and insights from the analysis.</p>

<ul>
  <li>Acceptance rates for Bar Coupons:</li>
    <ul>
      <li>Higher for people:</li>
        <ul>
          <li>between the age 25 to 30</li>
          <li>who go to the bar more than once a month,its highest for those who go to the bar more than 3 times </li>
          <li>who had passengers that were not a kid</li>
          <li>had occupations other than farming, fishing, or forestry</li>
          <li>were not widowed</li>
        </ul> 
    </ul>
    <ul>
      <li>Lower for those who go to cheap restaurants more than 4 times and income is less than 50K</li>
    </ul>
</ul>
<ul>
  <li>Acceptance rates for Coffe House Coupons:</li>
    <ul>
      <li>Higher for people:</li>
        <ul>
          <li>between the age 25 to 30</li>
          <li>who go to coffeehouse more than once</li>
          <li>has no kids and were not widowed</li>
          <li>had occupations other than farming, fishing, or forestry</li>
        </ul> 
    </ul>
    <ul>
      <li>Lower for those who go to cheap restaurants more than 4 times and income is less than 50K</li>
    </ul>
</ul>
  
<h3>Conclusion</h3>
<p>It will be beneficial to send Bar and Coffee House coupons to respective customer segments as listed in key findings</p>

<h3>Future Work</h3>
<p>Exploring other types of coupons and relate it to time of the day</p>

<h3>Repository Structure</h3>
<ul>
  <li><code>data/</code>: Contains dataset used in the analysis.</li>
  <li><code>on_route_coupon_acceptance_recommendation.jpynb</code>: Jupyter notebook with code for data analysis.</li>
  <li><code>README.md</code>: Summary of findings and link to notebook</li>
</ul>

<h2>Notebook</h2>
<p>The detailed analysis and code can be found in the Jupyter notebook <a href="https://github.com/mitbans/coupon-acceptance-analytics/blob/main/on_route_coupon_acceptance_recommendation.ipynb">here</a>.</p>
