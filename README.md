

---

# **Loan Default Risk Analysis Using EDA**

This project applies Exploratory Data Analysis (EDA) techniques to identify patterns and insights that help mitigate loan default risks in a consumer finance company. The analysis is aimed at understanding the factors influencing repayment capabilities, ensuring that creditworthy applicants are not rejected while minimizing financial risks.

---

## **Project Overview**

Loan providers face challenges in assessing loan applications due to insufficient credit histories, leading to either missed business opportunities or financial losses. This project analyzes consumer and loan attributes to identify key indicators of default risk, leveraging data-driven insights for better decision-making.

### **Key Objectives**
- Identify variables that strongly indicate loan default risk.
- Understand the influence of consumer attributes (e.g., income, employment) on repayment behavior.
- Provide actionable recommendations to improve risk assessment and loan approval processes.

---

## **Datasets Used**
1. **`application_data.csv`**:
   - Contains client information at the time of loan application.
   - Includes payment difficulties and related attributes.

2. **`previous_application.csv`**:
   - Details previous loan applications, including their status (Approved, Refused, etc.).

3. **`columns_description.csv`**:
   - A data dictionary explaining the variables in the datasets.

---

## **Analysis Approach**
1. **Data Understanding**:
   - Reviewed the datasets for completeness and consistency.
   - Interpreted variable meanings and their relevance to business objectives.

2. **Data Cleaning**:
   - Addressed missing values through imputation and column removal where necessary.
   - Identified and retained high-impact features.

3. **Exploratory Analysis**:
   - Conducted univariate, bivariate, and segmented univariate analysis to identify trends and patterns.
   - Assessed data imbalance and its impact on model predictions.
   - Derived new metrics for deeper insights.

4. **Visualization**:
   - Used intuitive plots to present findings, ensuring clarity and relevance to business needs.

---

## **Key Insights**
- **Income Stability**: Higher income levels significantly reduce default risks.
- **Loan Amounts**: Larger loans correlate with increased default probability.
- **Employment History**: Longer employment durations indicate greater repayment reliability.
- **Data Imbalance**: The target variable is highly imbalanced, requiring careful handling in predictive modeling.

---

## **Recommendations**
1. **Dynamic Loan Pricing**:
   - Adjust interest rates based on applicant risk profiles.
2. **Enhanced Risk Assessment**:
   - Incorporate derived metrics like income-to-loan ratios into credit scoring models.
3. **Policy Refinements**:
   - Implement stricter approval criteria for high-risk applicants.
4. **Customer Education**:
   - Develop programs to improve financial literacy among clients.

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loan-default-risk-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Loan_Default_Analysis.ipynb
   ```

---

## **Tools and Libraries**
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Tabulate

---

## **Acknowledgments**
This project was developed as part of an assignment to understand risk analytics in banking and financial services, emphasizing the role of EDA in data-driven decision-making.

---
