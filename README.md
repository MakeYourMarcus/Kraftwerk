# Overview

In this first practical application assignment of the program, you will seek to answer the question, “Will a customer accept the coupon?” The goal of this project is to use what you know about visualizations and 
probability distributions to distinguish between customers who accepted a driving coupon versus those who did not. 

# Data

This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. 
There are three possible answers people can choose from:

- “Right away”
- “Later, before the coupon expires”
- “No, I do not want the coupon”

The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).

# Deliverables
Your final submission should include a brief report of your findings that highlights the differences in those who accepted coupons and those who did not. Utilize the Matplotlib and Seaborn libraries to create a visualization using Python. 
Ensure that your findings are clearly stated in a separate section alongside actionable items and recommendations.

# Bar Coupon Analysis
1. Those who frequent the bar more often are more likely to accept bar coupons
2. Those who are between 25 and 30 who visit the bar at least once are more likely to accept bar coupons compared to any other demographic. This could indicate that younger individuals are more likely to accept coupons from bars.
3. Those who drive with passengers who are not kids are more likely to accept the bar coupon than drivers with kids.
4. Those who drive who are not widowed have a higher likelihood of accepting bar coupons.
5. Those who go to cheap restaurants more than 4 times a month and have an income less than 50,000 are more likely to accept bar coupons.
