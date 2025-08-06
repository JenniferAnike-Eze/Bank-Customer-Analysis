# Bank Customer Churn Analysis 
This project focuses on analyzing customer churn in a bank using Python and Jupyter Notebook. It involves understanding customer demographics, behavioral trends and identifying possible business insights to support strategic decision making.

# Files in this repository
- Notebook with full exploratory analysis
- 'Presentation.pptx' summarizing presentation of findings
- Final cleaned dataset
- Dataset and dictionary

# Dataset Description
 The dataset includes two sheets:
- **Customer**: Contains personal and demographic details (e.g. age, geography, gender)
- **Account**: Includes banking behavior (e.g. number of products, activity status, churn info). The two datasets were merged on the 'CustomerID' column.

# Objectives
- Understand demographic and behaviour of customers.
- Identify characteristics of customers more likely to churn.
- Generate insights that can help improve customer retention strategies

# Data Cleaning
- Merged 'Customer' and 'Account' sheets using 'CustomerId'.
- Handled missing values in 'Age' and 'Surname'.
- Dropped duplicate columns

# Key Insight 
- **Churn by Gender**: Female customers show a slightly higher churn rate than males.
- **Churn by Geography**: Customers from Germany have a significantly higher churn rate.
- **Churn by Number of Products**: Churn increases for customers with 3 or 4 products, indicating possible dissatisfaction.

# Recommendations 
- The bank should investigate reasons why more women are leaving. This could involve running customer satisfaction surveys or offering tailored financial products for women.
- Encourage customers with 1 product to adopt more services and also ensure customers with many products are not overwhelmed or underserved.
- Investigate service delivery gaps in Germany to reduce churn and also introduce retention strategies such as improved service or loyalty incentives.

# Tools Used 
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Git & GitHub
- PowerPoint for presentation