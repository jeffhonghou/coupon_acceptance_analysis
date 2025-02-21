# Coupon Acceptance Report
## Overview
This report highlights the key differences between drivers who accepted various types of coupons and those who did not. The goal is to identify patterns in customer behavior based on their preferences, habits, and demographic factors. This analysis will help refine marketing strategies for future coupon offers.
## Link to the Jupyter notebook
[My Jupyter notebook](https://github.com/jeffhonghou/coupon_acceptance_analysis/blob/main/prompt.ipynb)
## Key Findings
**1. Bar Coupons**
- Accepted by: Drivers who go to bars more than once a month and are under the age of 30.
- Non-acceptance: Drivers who visit bars less frequently or are older than 30 tend to disregard bar coupons.
  
**2. Coffee Coupons**
- Accepted by: Drivers who visit coffee houses more than once a month, have passengers who are not kids, and are not widowed.
- Non-acceptance: Drivers who have children as passengers or are widowed showed less interest in accepting coffee coupons.
  
**3. Less Expensive Restaurants (under `$20`) Coupons**
- Accepted by: Drivers who had passengers that were not kids and when the coupon’s expiration date was within 1 day.
- Non-acceptance: Drivers with children as passengers or when the coupon had more than a 1-day expiration window.
  
**4. More Expensive Restaurants (`$20 - $50`) Coupons**
- Accepted by: Drivers who visit cheap restaurants more than once a month, have passengers who are not kids, and are not widowed.
- Non-acceptance: Drivers who do not visit inexpensive restaurants frequently or are widowed were less likely to accept these coupons.
  
**5. Carry Out & Takeaway Coupons**
- Accepted by: Drivers who took the coupon between 2 PM and 6 PM, and when the expiration date was within 1 day.
- Non-acceptance: Drivers who either didn’t take the coupon during this time frame or had a longer expiration window tended to ignore these offers.
## Conclusion
The coupon acceptance data shows clear patterns based on customers' frequency of visits to certain types of establishments, their demographics, and the timing of the offer. Customers who engage with specific venues regularly (like bars or coffee houses) or who have certain passenger types (e.g., no children) are more likely to accept relevant coupons.