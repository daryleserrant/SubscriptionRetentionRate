# SubscriptionRetentionRate
Subscription Retention Rate Takehome Challenge. From *A Collection of Data Science Takehome Challenges* by Guilio Palombo.

## Challenge Description
Company XYZ started a subscription model in January, 2015. You get hired as a first data scientist at the end of August and, as a first task, you are asked to help executives understand how the subscription model is doing.

Therefore, you decide to pull data from all the users who subscribed in January and see, for each month, how many of them unsubscribed. In particular, your boss is interested in:

- A model that predicts monthly retention rate for the different subscription price points
- Based on your model, for each price point, what percentage of users is still subscribed after at least 12 months?
- How do user country and source affect subscription retention rate? How would you use these findings to improve the company revenue?

## Data
One table:
subscription - gives information about the user and his/her subscription status. Columns:
- **user_id**: the id of the user. Unique by user.
- **subscription_signup_date**: when the user signed up for the subscription.
- **subscription_monthly_cost**: how much the user pays each month for the subscription
- **source**: marketing acquisition channel (SEO/Ads/Friend Referral)
- **billing_cycles**: total billing cycles as of the end of August.
- **is_active**: whether the subscription is still active (1) or not (0). If billing cycles is 8, it means the user has still an active subscription.
