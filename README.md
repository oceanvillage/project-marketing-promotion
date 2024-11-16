# project-marketing-promotion

## Overview<br>
  Analyze a historical marketing promotion data to propose cost effective marketing promotion(s)<br>
  Conduct a multiple linear regression analysis to estimate sales from a combination of independent variables<br>
<br>

## Objective<br>
  Advise stakeholders the cost effective marketing promotion<br>
<br>

## Dataset<br>
 * The dataset has four parameters(TV,Radio,Social Media,Influencer) and Sales resulted<br>
 * TV and Influencer are categorical<br>
 * Radio and Social Media are quantitative<br>
<br>

## Verification of assumptions<br>
  Check if Radio and Social Media promotion expenses can be used for linear regression<br>
  <br>
![graph 1](/assets/graph_1.png)!<br>
This graph shows Linearity and No multicolinearity<br>
<br>
As each marketing promotion is independent from one another, the independence assumption is valid<br>
<br>
Next, check the normality<br>
![graph 2](/assets/graph_2.png)<br>
![graph 3](/assets/graph_3.png)<br>

<br>
Normality is held based on the followings<br>
<br>
 - The histgram shows approximately normal distribution<br>
 - Q-Q-plot is close to a straight line<br>
<br>
At last, let's check constant variance<br>
 <br>
![graph 3](/assets/graph_3.png)<br>
<br>
Residuals are similarly distributed and the assumption is met<br>
<br>
  All five assumptions are valid to use multiple linear regression<br> 
  (Linearity, Independence, Normality, Constant variance, Multicolinearity)<br>
<br>

## Result<br>
![table_1](/assets/table_1.png)<br>
  * After reviewing the data, TV and Radio are identified as having linear relation with Sales<br>
  * Switching from high to med TV promotional budget reduces sales by $75 million (95\% CI \[-82 -68\])<br>
  * Switching from high to low TV promotional budget reduces sales by $154 million (95\% CI \[-164 -145\])<br>
  * Radio has a positive coefficient of 2.97. i.e. Sales increases $3 million per $\$1$ million promotion in Radio.<br>
<br>
Therefore, clarify high TV promotion cost and then determine which is cost effective, either TV or Radio per $1 million investment
<br>


