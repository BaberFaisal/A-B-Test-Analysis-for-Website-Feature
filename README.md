# A/B Test Analysis for Website Feature

This repository contains a complete statistical analysis of an A/B test experiment evaluating a new website feature. The goal is to determine whether the feature positively impacts user conversion rates.

---

## File Included

- `A_B_Test_Analysis_for_Website_Feature.pdf`  

---

##  Objective

To evaluate whether the newly introduced website feature leads to a statistically and practically significant increase in user conversions compared to the control version of the site.

---

##  Methodology

The analysis follows these steps:

1. **Data Generation**  
   Simulated data for 5,000 users in each of the Control and Treatment groups over a 14-day test duration.

2. **Data Cleaning and Validation**
   - Checked for missing data 
   - Verified unique user assignment to groups   
   - Removed illogical records where clicks > page views  
   - Outliers acknowledged for mock data 

3. **Key Metrics Calculation**
   - Conversion Rate = Conversions / Users  
   - Observed metrics for Control and Treatment groups  
   - Lift calculation (relative improvement)

4. **Statistical Significance Testing**
   - Used Z-test for proportions  
   - Calculated p-value and 95% confidence interval  
   - Hypothesis testing conducted

5. **Power Analysis**
   - Computed effect size and statistical power  
   - Confirmed adequacy of sample size

6. **Practical Interpretation**
   - Evaluated uplift significance  
   - Provided rollout recommendations

---

## 📈 Results Summary

| Metric                        | Control Group | Treatment Group |
|------------------------------|---------------|------------------|
| Users                        | 5,000         | 5,000            |
| Conversions                  | 479           | 590              |
| Conversion Rate              | 9.58%         | 11.80%           |
| Observed Difference          | —             | **+2.22%**       |
| Relative Uplift              | —             | **+23.17%**      |
| p-value                      | —             | **0.00033**      |
| 95% Confidence Interval      | —             | [1.01%, 3.43%]   |
| Statistical Power            | —             | 94.9%            |

---

##  Conclusion

- The new website feature **significantly increases** user conversion rates.
- The difference is both **statistically significant** and **practically meaningful**.
- **Recommendation**:  **Roll out the feature** to the wider user base.
