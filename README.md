Welcome to My GitHub Profile!

About Me

Hello! My name is William, My focus lies in leveraging data to build meaningful models, pipelines, and systems that enhance decision-making and operational efficiency. On this GitHub page, you’ll find some of my recent projects that reflect my passion for data analysis, machine learning, and process automation.

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

4. NFL Fantasy Football Dataset
Project Overview:

This project involves building a comprehensive NFL Fantasy Football (FF) dataset using nfl_data_py to support predictive modeling and advanced analytics for fantasy football strategies. The dataset encompasses player statistics, weekly performance data, injury history, and defensive team stats from the 2020 to 2023 NFL seasons, making it suitable for both exploratory data analysis and machine learning applications.

The dataset was constructed by aggregating various NFL statistics and merging them with player metadata and seasonal rosters. It can be used for building fantasy point prediction models, player ranking systems, and injury analysis to enhance fantasy team management. 

File Names:
•	nfl_season_data.csv: The complete cleaned dataset combining player performance, fantasy statistics, and injury data.
•	nfl_team_defense_data.csv: Dataset containing defensive statistics for all NFL teams.
•	nfl_draft_picks.csv: Data for NFL draft picks for the 2024 season.

Data Sources:
A.	nfl_data_py: Primary data extraction library used to gather weekly, seasonal, and player-level data.
B.	Pro-Football-Reference.com: Supplementary source for team-level statistics and defense data.

Dataset Structure and Key Columns:

Player Information:
	•	player_id: Unique identifier for each player.
	•	player_name: Full name of the player.
	•	position: The position played by the player (e.g., QB, RB, WR).
•	player_team: The team for which the player is currently playing
 
 Weekly Performance Data:
	•	week: NFL week of the season.
	•	completions, attempts, passing_yards, passing_tds: Passing statistics.
	•	carries, rushing_yards, rushing_tds: Rushing statistics.
	•	receptions, targets, receiving_yards, receiving_tds: Receiving statistics.
	•	fantasy_points, fantasy_points_ppr: Total fantasy points scored by the player for that week.

Advanced Metrics:
	•	target_share, air_yards_share, wopr: Advanced metrics measuring player usage and efficiency.
	•	passing_epa, rushing_epa, receiving_epa: Expected Points Added (EPA) metrics.

Injury Data:
	•	report_primary_injury: The primary injury reported for a player.
	•	practice_status: Practice participation status.
•	report_status: Game day availability status (Active, Questionable, Out).

Defensive Team Stats:
•	team_defense_data.csv: Includes defensive team statistics, opponent yards allowed, and scoring statistics.

Key Steps in Building the Dataset:

Data Import and Initial Inspection:
•	Imported player metadata and seasonal rosters using nfl_data_py to establish a base dataset.
•	Extracted weekly performance data from the NFL’s official records dating back to 2020.
•	Previewed columns to identify necessary fields for fantasy prediction and player analysis.

Data Cleaning and Preprocessing:
•	Removed unnecessary columns and handled missing values using data imputation techniques.
•	Standardized player and team names to ensure consistency across datasets.
•	Downcasted numeric values to optimize memory usage for larger datasets.

Data Merging:
•	Merged player metadata with weekly performance data to create a single comprehensive dataset.
•	Integrated defensive stats to include opponent team performance for context.
•	Added recent injury history to enhance predictive modeling capabilities.

Advanced Statistics and Filtering:
•	Filtered the dataset for specific player positions (QB, RB, WR, TE, K) to focus on key contributors to fantasy scoring.
•	Aggregated fantasy points for the last three seasons to identify top players by position.

Defensive Team Analysis:
•	Imported and analyzed team defense data to evaluate the impact of opposing defenses on player performance.

Usage Instructions:

This dataset is ideal for building fantasy football prediction models, performing player performance analysis, and conducting advanced statistical analysis. Users can apply it to:

•	Predict Fantasy Points: Train machine learning models to forecast weekly player performance.
•	Identify Top Players: Use historical data to rank players and identify potential breakout candidates.
•	Analyze Injury Impact: Study the effect of injuries on player productivity and game availability.

# Code to load the dataset:
import pandas as pd

# Load the main dataset
nfl_data = pd.read_csv('nfl_season_data.csv')

Note: I do currently have the prediction model in the final stages and will upload to the repository when its ready. 
----------------------------------------------------------------------------------------------------------------------------
🚀 What’s Next?

I’m continuously adding new projects as I advance my learning in machine learning, cloud computing, and systems integration. A few things I have in the works now are a NFL statistic prediction model capable of prediction fantasy scores and upcoming games using data from previous seasons. Ive included injuries, statidiums and weather. Im currently in the final stages of training. I am also working on a Loan Default dataset. The dataset is completed and I am building some vizualizations. Stay tuned for more updates, including my upcoming work and feel free to give any feedback as Im always open to learning new and more efficient ways to complete these projects. 

📫 Get in Touch

Feel free to reach out to me for any collaboration, feedback, or discussions about data, programming, or technology in general. You can contact me via email.
