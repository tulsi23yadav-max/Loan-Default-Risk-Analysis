# Loan Default Risk Analysis

## Project Overview
This project analyzes loan data to understand borrower repayment behaviour and identify factors associated with loan defaults.

The analysis was performed using Python, Pandas, NumPy, Matplotlib and Seaborn in Jupyter Notebook.

## Objectives
- Understand loan repayment and default patterns.
- Analyze default rates across loan grades.
- Examine the relationship between interest rates and defaults.
- Compare default rates across loan purposes and income groups.
- Clean and prepare the dataset for analysis.

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset
The project uses the accepted loan dataset covering 2007–2018 Q4.

For this analysis, a sample of 100,000 records and 16 selected columns was loaded into the notebook.

The selected fields include loan amount, interest rate, grade, employment length, annual income, loan status, purpose and debt-to-income ratio.

## Data Preparation
- Checked dataset structure and data types.
- Checked duplicate records.
- Identified missing values.
- Filled missing employment length values with "Unknown".
- Removed rows with missing DTI or revolving utilisation values.
- Created a default indicator for completed loan outcomes.

## Key Findings

- The analysis covered 100,000 records.
- The dataset contained no duplicate rows.
- After cleaning, 99,961 records remained.
- Among 87,854 completed loan outcomes, the calculated default rate was 20.03%.
- Grade A had a default rate of 5.32%, while Grade G had a rate of 59.05%.
- Loans with interest rates above 20% had a default rate of 52.56%.
- The small business loan-purpose category showed a default rate of 29.95%.
- The below-25K income group showed a default rate of 22.95%.


## Conclusion
The analysis shows differences in default rates across loan grades, interest-rate groups, loan purposes and income groups. These patterns can help support further investigation of borrower risk.

*Note: These findings describe the analyzed sample and should not be treated as proof that any single factor causes loan default.*
