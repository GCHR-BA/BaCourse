# Approach Questions

1. Purchase Intent
How might you determine if the size of a specific product is a significant feature in determining the customer's calculated propensity to buy it?

2. Metrics to Acquire Customers
What metrics would you use to track whether Uber's strategy of using paid advertising to acquire customers works?

3. Finding Invalid Schools
How many high schools that people have listed on their Facebook profiles are real? How do we find out, and deploy at scale, a way of finding invalid schools?

4. Active User Probability
How would you test whether having more friends now increases the probability that a Facebook member is still an active user after 6 months?

5. Predict Next Item
Given an existing set of purchases, how do you predict the next item to purchase of a new basket?

6. Users in Meaningful Segments
How do you take millions of users with 100's of transactions each, amongst 10k's of products and group the users together in meaningful segments?

7. McD's Big Macs
How many Big Mac does McDonald sell each year in South Korea?

8. Estimating Birthdays
Facebook would like to develop a way to estimate the month and day of people's birthdays, regardless of whether people give them that information directly. What methods would you propose, and data would you use, to help with that task?

Sample Solution: We can estimate the users' birthday by looking into their engagements, if the engagements spike in a certain month or day, it's highly possible that the user is born on that day, because user might post, tag, send or receive lots of messages on their birthday. To be more cautious, if data from the past 5 years show the similar pattern, it's highly possible that the user is born on that day.

9. Anti-Dentite
How many dentists are there in South Korea?

10. Financial Institution
How would a financial institution determine if an applicant makes more or less than $50k/year?

11. Windows in South Korea
How many windows are there in South Korea?

12. Increase Number of Customers
Suppose you have a coffee store, what do you do to increase the number of customers?

13. Double the Number of Ads
If a PM says that they want to double the number of ads in Newsfeed, how would you figure out if this is a good idea or not?

Sample solution: 
Goal: increase revenue

A/B Test Groups

    Test: double # of ads
    Control: same # of ads

Test Metrics

    Success mean of CTR for each group
    Guardrail mean session time
    Guardrail mean bounce rate 

Test Type

    MANOVA Test

Additional Considerations 1. How much change can we allow in the guardrail metrics (e.g. decrease in avg. session time/ increase in avg. bounce rate) for a given increase in success metric (e.g. CTR)? 2. Is there an alternative way to maximize revenue (e.g. increase ads by 30% or show ads at certain times) without decreasing user engagement/retention.

Results: -Double # of ads if:

    CTR increases
    mean session time increases
    bounce rate decreases

14. Demand
How would you identify if an increase in sales for a product is due to organic demand or one off event?

15. Cost of Discount Coupons
A $5 discount coupon is given to N riders. The probability of using a coupon is P. What is the expected cost for the company?

16. Influencer Metrics
How would you quantify the influence of a Twitter user?

17. Investigate the Discrepancy
If 70% of Facebook users on iOS use Instagram, but only 35% of Facebook users on Android use Instagram, how would you investigate the discrepancy?

18. Two Metrics Discrepancy
There is an increase of users who feel their privacy is respected by 8%, but the engagement to Google Play Services has decreased by 14%. How would you investigate this discrepancy?







