# Metadata on `diff_in_diff.csv`

The file `diff_in_diff.csv` contains historical data from the e-commerce company. In this dataset, the discount was **not randomly assigned**. 
Here is what we know about how discounts were distributed:

1. At some point in time, the e-commerce company started giving discount coupons to women on Mother’s Day.
2. At some point in time, the company started testing more aggressive discounting in the state MG.

Here are all the columns and a brief description of what they represent.

1. sales: long-term sales for that customer – this is a possible outcome variable; it should not be used as a feature;
2. discount: amount of discount given to the customer at the moment they joined the platform;
3. profit: long-term profit for that customer – profit is given by the formula 5% sales - discount;
4. age: customer age – self-reported;
5. gender: customer gender – can be “W” for women, “M” for men, “O” for others, or empty if not reported;
6. cust_state: customer address state – last address used for delivery – provided at customer onboarding stage;
7. tenure: time since customer joined the platform in months;
8. month: time index in month – month 0 is the first month the e-commerce started doing business, month 1 is the second month, and so on.