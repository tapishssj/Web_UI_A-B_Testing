Business request:
To determine if the difference in click rates between the experimental(exp) and control(con) groups is statistically significant.

Process:
The exp group is shown the new webpage design, while the con group sees the original design.
The script simulates user interactions and calculates the click-through rate for each group.
Statistically analyze the results to assess if the new design significantly improves user engagement.


Method:
Step 1: Calculate total number of clicks (X_con, X_exp) and click probabilities (p_con_hat, p_exp_hat) for each group.

Step 2: Compute a pooled click probability (p_pooled_hat) and pooled variance.

Step 3: Calculate standard error (SE) to measure the precision of click probability estimates.

Step 4:Perform a two-sample Z-test (calculates test statistic (Test_stat), critical value (Z_crit), and p-value).

Step 5:Determine a confidence interval (CI) to estimate the true difference in click probabilities.

Findings:
The script provides statistical evidence on whether the new design (experimental group) leads to a higher click rate compared to the control group.
