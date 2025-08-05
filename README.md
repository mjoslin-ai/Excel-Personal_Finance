# Excel-Personal_Finance

This analysis will demonstrate how financial literacy mitigates stress, reinforcing the importance of investing knowledge for financial well-being. The approach leverages Excel’s tools (pivot tables, formulas, charts, and statistical functions) while addressing data nuances like "99" (prefer not to say) values. Below, I outline the methodology, including data preparation, analysis steps, visualization, and interpretation, tailored to the NFCS 2024 dataset ("NFCS 2024 State Data 250623.csv" and "NFCS-2024-State-by-State-Questionnaire.pdf").

## Objective

Determine if respondents with higher financial literacy scores (based on correct answers to M6-M10, M31, M50) report lower financial stress (higher confidence of covering an unexpected need of $2,000 within the next month, J20). This supports the argument that understanding investing and personal finance reduces anxiety, emphasizing the value of financial education.

## Steps

### 1: Data Preparation

1. Load the Dataset
   - Open "NFCS 2024 State Data 250623.csv" using Data > From Text/CSV 
3. Handle "98"/"99" (don't know/prefer not to say) Values
   - For each literacy question (e.g., M6), exclude "99", "98" can be interpreted aa an incorrect response
   - For J20, exclude both "98" and "99" as these responses are non-substantive for this analysis
5. Create Financial Literacy Score
   - 

### 2. 
