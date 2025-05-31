# prodigy_DS_02
Overview
This Jupyter Notebook analyzes a dataset related to loan approvals, exploring various factors that influence whether a loan is approved or not. The dataset includes information such as applicant income, credit history, property area, and loan status.

Features
Data Loading: Loads the loan dataset from a CSV file.

Data Cleaning: Handles missing values by filling them with appropriate measures (mode for categorical variables, median for numerical variables).

Exploratory Data Analysis (EDA):

Visualizes loan approval status using count plots.

Analyzes the relationship between loan approval and property area.

Examines the distribution of loan approvals by gender.

Feature Engineering: Creates a new feature, Total_Income, by combining applicant and coapplicant income.

Visualizations
Loan Approval Status: A count plot showing the distribution of approved (Y) and rejected (N) loans.

Loan Status by Property Area: A count plot illustrating how loan approval varies across urban, rural, and semiurban areas.

Loan Status by Gender: A histogram comparing loan approvals between male and female applicants.

Libraries Used
Pandas: For data manipulation and analysis.

Seaborn: For statistical data visualization.

Matplotlib: For creating static, interactive, and animated visualizations.

Plotly: For interactive visualizations.



Dataset
The dataset contains 614 entries with the following columns:

Loan_ID: Unique identifier for each loan application.

Gender: Applicant's gender.

Married: Marital status.

Dependents: Number of dependents.

Education: Applicant's education level.

Self_Employed: Whether the applicant is self-employed.

ApplicantIncome: Income of the applicant.

CoapplicantIncome: Income of the coapplicant.

LoanAmount: Loan amount requested.

Loan_Amount_Term: Term of the loan.

Credit_History: Credit history of the applicant.

Property_Area: Location of the property.

Loan_Status: Status of the loan (Y/N).

