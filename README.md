Welcome to My GitHub Profile!

About Me

Hello! My name is William, I am a data analyst and aspiring software engineer, currently working towards a Bachelor’s in Computer Science and a Google Data Analytics Certification. My focus lies in leveraging data to build meaningful models, pipelines, and systems that enhance decision-making and operational efficiency. On this GitHub page, you’ll find some of my recent projects that reflect my passion for data analysis, machine learning, and process automation.

📂 Projects

1. Fraud Detection Model

In this project, I developed a comprehensive fraud detection model that analyzes transaction data to identify potential fraudulent activity. The notebook walks through the process of data cleaning, feature engineering, model selection, and evaluation. It showcases the use of various machine learning techniques and highlights the importance of balancing accuracy with recall when dealing with imbalanced datasets.

Key Features:

• Data preprocessing and cleaning
• Feature engineering
• Model evaluation and performance tuning
• Integration of fraud detection metrics

You can explore the notebook here.

2. Data Processing Pipeline

This project demonstrates an end-to-end data processing pipeline built for handling and transforming raw data before feeding it into machine learning models. The pipeline is designed to be modular, ensuring easy integration with different datasets and workflows. It also handles feature selection, scaling, and encoding of categorical variables, making it highly flexible for various projects.

Key Features:

• Modular pipeline structure
• Data transformation and scaling
• Categorical feature encoding
• Feature selection and extraction

You can explore the pipeline here.

3. Banking Dataset for Customer Churn Analysis

Dataset Overview:

This dataset contains information about bank customers and their account details, which was used to analyze and predict customer churn. The dataset was cleaned and preprocessed to handle missing values, outliers, and categorical encoding to make it suitable for analysis and machine learning tasks.

File Name:

cleaned_banking_data.csv

Columns and Descriptions:

1. CustomerId (Integer): Unique identifier for each customer.
2. Surname (String): The last name of the customer.
3. CreditScore (Integer): Credit score of the customer, ranging from 350 to 850.
4. Geography (String): The country of residence (e.g., France, Spain, Germany).
5. Gender (String): Gender of the customer (Male/Female).
6. Age (Integer): Age of the customer.
7. Tenure (Integer): Number of years the customer has been with the bank.
8. Balance (Float): Account balance of the customer.
9. NumOfProducts (Integer): Number of bank products the customer is subscribed to.
10. HasCrCard (Integer): Whether the customer has a credit card (1 = Yes, 0 = No).
11. IsActiveMember (Integer): Whether the customer is an active member (1 = Yes, 0 = No).
12. EstimatedSalary (Float): Estimated annual salary of the customer.
13. Exited (Integer): Whether the customer has exited the bank (1 = Yes, 0 = No).

Data Cleaning and Preprocessing Steps:

Handling Missing Values:
• Missing values were imputed using the most frequently occurring value for categorical columns (Geography, Gender) and the mean/median for numerical columns (CreditScore, Age).

Encoding Categorical Variables:
• Converted the Gender and Geography columns into numeric values using one-hot encoding to make them suitable for modeling.

Outlier Detection and Treatment:
• Identified and removed outliers in CreditScore using the Interquartile Range (IQR) method to avoid skewing the analysis.
 
Feature Scaling:
• Normalized EstimatedSalary and Balance columns using StandardScaler to ensure that all features are on a similar scale for analysis.

Transformation of Binary Columns:
• Modified binary columns (HasCrCard, IsActiveMember, Exited) to retain their numeric values (1 = Yes, 0 = No) but included descriptive labels for clarity in documentation.

Usage Instructions:

This dataset is primarily used for building predictive models to identify customers at risk of churning. It can also be used for:

• Exploratory Data Analysis (EDA) to understand patterns and correlations.
• Feature engineering and testing different model architectures (e.g., Random Forest, Logistic Regression).
• Creating visualizations to identify insights such as churn rates by geography, product usage patterns, and customer demographics.

Potential Use Cases:

A. Predicting Customer Churn:
• Train machine learning models to predict whether a customer is likely to exit the bank based on historical data.
B. Segmentation Analysis:
• Identify different customer segments (e.g., high-risk churn groups, high-value customers) to inform marketing and retention strategies.
C. Business Insights:
• Use visualizations to inform business decisions, such as adjusting offerings for customers with high credit scores or targeting specific age groups.

Data Source:
I used the Churn_Modelling.csv (shubham meshram - Owner)from Kaggle. The dataset is a commonly used dataset for predicting customer churn in the banking industry. It contains information on bank customers who either left the bank or continue to be a customer. The dataset includes the following attributes:

Customer ID: A unique identifier for each customer
Surname: The customer's surname or last name
Credit Score: A numerical value representing the customer's credit score
Geography: The country where the customer resides (France, Spain or Germany)
Gender: The customer's gender (Male or Female)
Age: The customer's age.
Tenure: The number of years the customer has been with the bank
Balance: The customer's account balance
NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
EstimatedSalary: The estimated salary of the customer
Exited: Whether the customer has churned (1 = yes, 0 = no)

🚀 What’s Next?

I’m continuously adding new projects as I advance my learning in machine learning, cloud computing, and systems integration. A few things I have in the works now are a NFL statistic prediction model capable of prediction fantasy scores and upcoming games using data from previous seasons. Ive included injuries, statidiums and weather. Im currently in the final stages of training. I am also working on a Loan Default dataset. The dataset is completed and I am building some vizualizations. Stay tuned for more updates, including my upcoming work and feel free to give any feedback as Im always open to learning new and more efficient ways to complete these projects. 

📫 Get in Touch

Feel free to reach out to me for any collaboration, feedback, or discussions about data, programming, or technology in general. You can contact me via email.
