### **Big Data Final Project: Analysis of the 1994 USA Census Income Data Set**

- **Notebook Link**: [View Notebook on Databricks](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/753555617520967/2613570139713025/4332491155661788/latest.html?classId=6d95e7f2-4dcb-46a4-8323-a5ea48c1f354&assignmentId=8423c969-43a7-4269-aace-31df2082793c&submissionId=0be25e27-2912-bd18-f2de-84e5c176c21d)

**Authors:** Roberto Perez Delgado, Sanchez Manyika, and Jose Martin Campos Silva

#### **Overview:**
This project involved an in-depth analysis of the 1994 USA Census Income Data Set, which consists of 48,842 observations with 14 input variables and a binary target variable (annual salary <= or > $50,000). The primary goal was to explore the dataset using SQL queries, visualize key insights through charts, and develop a predictive model to classify whether an individual earns more or less than $50,000 annually.

#### **Key Components:**

1. **Data Preprocessing:**
   - Converted the original `.data` file format to `.csv` for compatibility.
   - Uploaded and displayed the dataset using Databricks.
   - Conducted initial exploratory data analysis (EDA) to understand the distribution of variables.

2. **SQL Queries and Data Visualization:**
   - Performed various SQL queries to extract insights, such as:
     - Minimum, maximum, and average age per sex.
     - Salary distribution across different education levels.
     - Gender distribution across occupations.
     - Proportions of individuals earning more or less than $50K by race, education, and marital status.
   - Generated visualizations to support the findings, including several pie charts and bar chart.

3. **Predictive Modeling:**
   - Created a pandas dataframe from the dataset for modeling.
   - Displayed a correlation matrix of numerical variables, revealing minimal correlation, indicating potential for predictive modeling.
   - Implemented a Logistic Regression model to predict whether an individual's annual salary exceeds $50K.
   - Conducted feature selection to refine the model by focusing on the most predictive variables.
   - Evaluated model performance by comparing predicted probabilities with actual outcomes.

4. **Model Results:**
   - The final logistic regression model demonstrated a strong predictive ability, accurately classifying individuals based on their attributes.

#### **Technologies Used:**
- **Databricks** for data processing and SQL querying.
- **Python** (Pandas, NumPy, Matplotlib, Seaborn) for data manipulation, visualization, and modeling.
- **SQL** for querying and extracting insights from the dataset.
- **Scikit-learn** and **Statsmodels** for machine learning and statistical modeling.

#### **Dataset:**
- **Source:** [1994 USA Census Income Data Set](https://archive.ics.uci.edu/ml/datasets/Census+Income)
- **Size:** 48,842 observations, 14 input variables, 1 binary target variable (annual salary <= or > $50,000).
