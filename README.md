This is the project for Machine learning certification course by berkley 

Practical Application Assignment 5.1: Will the Customer Accept the Coupon?

Here is the notebook link for the analysis that was done for this project - 

Problem Statement - The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not. 

Approach - Data that was given for this project comes from UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. T

Analysis Summary - Apprach i took was first analyze coupon on Bar type and do analysis on how does it relate to people going to a Bar. Based on the analysis i came to conculsion there is more probablity of people accepting Bar coupons who go to bar 4 times more a iek. 

I then extended the same analysis to Carry out coupons 

Detailed Analysis - Here are few steps that are performed during detailed analysis 

For detailed data quality analysis, looked at value counts for each column. based on that i deducted data was in fairly good shape. i replaced null on Bar column with never but no need to do any more data clean up 

First few steps ire what ire given in the notebook to do the Bar analysis. i looked at various dat apoint son how frequent a person goes to Bar and what is the probablity for that person to accept coupons. Based on above observation i can deduct probablity of people accepting coupons who goes to bar three times or less is highest 

Then i wanted to deduct based on each data value/column who has more probablity of accepting or not accepting coupons. So i did loop over all columns and group by count on Y or N. Based on analysis i  can see from data Carry away coupons are most accepted ones. After than Restaurants < 20 are other accepted coupons

I then focussed  analysis on our dataset for only Carry away coupons. I did a group by for each column value to figure which other value has impact wether coupon is accepted or not. Based on group by analysis we can deduct that people who are staying Alone, has_children 0 , direction_same = 0 are most likely to accept the coupon. We did a comparitive analysis to then prove the theory

Next steps - 
We can extend similar analysis to other coupon types 
Also we can do more analysis on why coupons were not accepted. This can help putting more focus saying a certain population does not accept then we can divert efforts 