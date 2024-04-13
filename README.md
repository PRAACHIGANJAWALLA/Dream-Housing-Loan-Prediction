### Predict Loan Eligibility for Dream Housing Finance
Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.

Listed below are the Data Columns:
| Column Name        | Data Type |
|--------------------|-----------|
| Loan_ID            | object    |
| Gender             | object    |
| Married            | object    |
| Dependents         | object    |
| Education          | object    |
| Self_Employed      | object    |
| ApplicantIncome    | int64     |
| CoapplicantIncome  | float64   |
| LoanAmount         | float64   |
| Loan_Amount_Term   | float64   |
| Credit_History     | float64   |
| Property_Area      | object    |
| Loan_Status        | object    |

I Predicted Loan Eligibility for Dream Housing Finance company using 
1. Decision Tree Classifier 
2. Logistic Regression
3. K Nearest Neighbor
4. Random Forest
5. Support Vector Classifier
