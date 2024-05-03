<h1>Exploratory Data Analysis of Coupon Marketing data to determine customer behavior in accpeting the coupons while driving</h1>


<b>Workflow:</b>
  <ul>
  <li>Step 1: Understand and Read in the Data</li>
  <li>Step 2: Understanding the Features</li>
  <li>Step 3: Business Objective: Distinguish between customers who accepted a driving coupon versus those that did not.</li>
  <li>Step 4: Engineering Features</li>
  <li>Step 5: Plotting, statistical summarization and data visualization </li>
  <li>Step 6: Coupon Recommendations</li>
  </ul>




<h1>Will a Customer Accept the Coupon?</h1>

<h2>Summary of Findings</h2>

<h3>Introduction</h3>
<p>This repository contains the code and analysis for "On route coupon acceptance while driving". The project aimed to distinguish between customers who accepted a driving coupon versus those that did not.</p>

<h3>Data</h3>
<p>This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).</p>

<h3>Methodology</h3>
<p>Overview of the methodologies, techniques, and algorithms used for analysis.</p>
<ul>
  <li>Exploratory Data Analysis (EDA)</li>
  <li>Statistical summary</li>
  <li>Data Visualization using Matplotlib, Seaborn and Plotly libraries</li>
</ul>

<h3>Results</h3>
<p>Key findings and insights from the analysis.</p>

<ul>

  <li>Conclusion Bar Coupons:</li>
  
    <ul>
      <li>Acceptance rates are higher for people:</li>
        <ul>
          <li>between the age 25 to 30</li>
          <li>who go to the bar more than once a month,its highest for those who go to the bar more than 3 times </li>
          <li>who had passengers that were not a kid</li>
          <li>had occupations other than farming, fishing, or forestry</li>
          <li>were not widowed</li>
        </ul> 
        <ul>
          <li>Accpetance rates are lower for those who go to cheap restaurants more than 4 times and income is less than 50K</li>
        </ul>
      </ul>
</ul>
  
<h3>Conclusion</h3>
<p>Summary of the project's outcomes and any actionable insights.</p>

<h3>Future Work</h3>
<p>Potential areas for further exploration or improvement.</p>

<h3>Repository Structure</h3>
<ul>
  <li><code>notebooks/</code>: Contains Jupyter notebooks with code for data analysis.</li>
  <li><code>data/</code>: Contains datasets used in the analysis.</li>
  <li><code>scripts/</code>: Additional scripts or utility functions used in the project.</li>
  <li><code>README.md</code>: Detailed instructions and documentation for running the code.</li>
</ul>

<h2>Notebook</h2>
<p>The detailed analysis and code can be found in the Jupyter notebook <a href="link-to-notebook">here</a>.</p>
