## Introducing potential outcomes to DiD

- Models do not make things causal, treatment assignment mechanisms are what make things causa l
- Diff-in-diff can be used to only estimate ATT (Average treatment effect on the treated)
- Diff-in-diff = ATT + Parallel trends Bias
- t - treated 
- u - untreated
- Post - post treatment
- Pre - pre treatment
- d_hat (DiD) = (E[Y1t|Post] - E[Y0t|Pre]) - (E[Y1u|Post] - E[Y0u|Pre])
- which essentially equals the switching equation
- adding a zero term E[Y0t|Post] - E[Y0t|Post] the counterfactual for the treated if they were not 
- 