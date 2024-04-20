# Variable metadata
Markdown file containing meta-information about the variables of the datset.

## Variables

- log.annual.inc:
	* This feature represents the natural logarithm of the borrower's self-reported annual income.
	* Using the natural logarithm helps in transforming the income data to a more interpretable scale and reduces the skewness often present in income distributions.
	* Higher values of log.annual.inc indicate higher annual incomes for borrowers.

- dti (Debt-to-Income Ratio):
	* The debt-to-income ratio is a financial metric that measures the borrower's total debt payments divided by their gross income.
	* It indicates the proportion of the borrower's income that goes toward debt repayment each month.
	* A higher dti implies that the borrower has a higher level of debt relative to their income, which may increase the risk of defaulting on a loan.
- fico (FICO Credit Score):
	* FICO credit score is a numeric representation of a borrower's creditworthiness based on their credit history.
	* It ranges typically from 300 to 850, with higher scores indicating lower credit risk.
	* Lenders often use FICO scores to assess the likelihood of a borrower defaulting on a loan.
	* Lower FICO scores suggest a higher risk of default, while higher scores indicate lower risk.
- days.with.cr.line (Days with Credit Line):
	* This feature represents the number of days the borrower has had a credit line.
	* It reflects the borrower's credit history and the length of time they have been managing credit accounts.
	* Generally, a longer credit history is considered favorable, as it demonstrates responsible credit management behavior.
- revol.bal (Revolving Balance):
	* Revolving balance refers to the amount of unpaid debt remaining on a borrower's credit card at the end of a billing cycle.
	* It represents the outstanding balance that accrues interest charges if not paid in full.
	* Higher values of revol.bal indicate higher levels of outstanding debt.
- revol.util (Revolving Line Utilization Rate):
	* Revolving line utilization rate measures the proportion of the borrower's available credit that is being utilized.
	* It is calculated by dividing the borrower's revolving balance by their total credit limit.
	* Higher revol.util values indicate that the borrower is using a larger percentage of their available credit, which can negatively impact their credit score and increase the risk of default.
- inq.last.6mths (Inquiries in the Last 6 Months):
	* This feature represents the number of inquiries made by creditors on the borrower's credit report in the last 6 months.
	* Credit inquiries occur when lenders or creditors check a borrower's credit report in response to a credit application.
	* Multiple inquiries within a short period may suggest that the borrower is seeking credit from multiple sources, potentially indicating financial instability.
- delinq.2yrs (Delinquencies in the Past 2 Years):
	* Delinquencies refer to instances where the borrower has been late on payments by 30 days or more.
	* delinq.2yrs represents the number of times the borrower has been delinquent on payments in the past 2 years.
	* Higher values indicate a history of payment difficulties, which may increase the risk of default.
- pub.rec (Public Records):
	* Public records include derogatory information such as bankruptcy filings, tax liens, or judgments against the borrower.
	* pub.rec represents the number of derogatory public records associated with the borrower's credit report.
	* Higher values indicate a more adverse credit history, which can negatively impact the borrower's creditworthiness and increase the risk of default.