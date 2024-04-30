# Estimating the profitability of discounts

We help an e-commerce company understand the impact of its discounting strategy. We don't have data where discounts are randomly assigned, which makes estimating its impact challenging.

We know that the treatment assignment mechanism is based on giving discounts according to sales predictions from a machine learning model. Customers with high predicted sales get more discount.
The assumption was that more discounts generate more profits, when, in fact, discounts were given to customers that were already more profitable in the first place.

We adjust for the confounder sales prediction using regression to see how we can expect profits to change for a unit change in discount while keeping sales prediction fixed.

We conclude that:
* The company is giving more discounts to customers that are already generating more profits
* Once adjusted for sales prediction, the discount seems to decrease profits, on average

Learnt in this project:
* Basics of adjusting for bias to estimate the average treatment effect

Next up:
* Natural experiments - regression discontinuity design, diff-in-diff
* How to move from estimating the average treatment effect to estimating the individual treatment effect in order to personalize the treatment

This project is a part of the [Causal Inference and Personalization](https://www.manning.com/liveprojectseries/causal-inference-ser) series on Manning.
