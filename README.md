Loan Default Risk Analysis — Horizon Financial Group

Project Overview

Horizon Financial Group wanted to understand why its personal-loan default rate was exceeding its target of 12%. I used Excel to examine borrower characteristics, loan attributes, and repayment outcomes to identify patterns associated with loan defaults and support a review of the company's lending process.

The dataset contained 601 loan records and 25 columns. I used Power Query to combine two datasets using borrower ID,and created categories for credit scores, debt-to-income (DTI) ratios, and years of employment.

Key Findings:

1. Overall loan default rate

The portfolio recorded 146 defaults among 601 loans, giving an overall default rate of 24.29%. This exceeded the company's 12% target by approximately 12.29 percentage points.

2. Credit score and default risk

The 520–599 credit-score bracket had the highest reported default rate, at 49.14%. Credit score also had the strongest absolute correlation with the default indicator among the variables examined (−0.286), suggesting that higher credit scores were associated with lower default values in this dataset.

3. Debt-to-income ratio

The analysis indicated that the DTI category above 60% was associated with a negative financial outcome in the historical portfolio. This suggests that high-DTI loans warrant further investigation. The proposed 60% threshold should be validated against the number of affected loans, default rates, and financial outcomes before being adopted as a lending rule.

4. Loan purpose and employment

Wedding loans recorded the highest reported default rate, at 32.14%. Borrowers working part-time with less than two years of employment had a reported default rate of 55.56%. These patterns should be interpreted alongside group sizes to determine how reliable the comparisons are.

5. Correlation analysis

The reported correlations with the default indicator were −0.286 for credit score, 0.198 for interest rate, 0.192 for DTI, 0.08155 for income, and 0.0181 for loan amount. Credit score had the strongest absolute correlation among these variables. Correlation indicates association, not causation.

Recommendations:

- Review the underwriting outcomes for lower credit-score brackets, particularly the 520–599 group.
- Investigate loans with DTI ratios above 60%, and test alternative thresholds before implementing a cutoff.
- Examine default outcomes by loan purpose and employment history, while accounting for the number of loans in each group.
- Validate the financial calculations behind revenue, losses, and net profit, including the assumptions used to calculate each measure.
- Monitor the default rate against the company's 12% target using a consistent reporting method.

Conclusion:

This project used Excel-based data preparation, segmentation, correlation analysis, and dashboard visualisation to investigate patterns in personal-loan defaults. The findings highlight credit score, DTI, loan purpose, and employment history as areas for further review. Additional validation would be needed before using these findings to change lending policies.

Tools Used:

Microsoft Excel, Power Query, Excel formulas, correlation analysis, and dashboard visualisation.
