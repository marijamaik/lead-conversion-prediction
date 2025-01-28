# ExtraaLearn Lead Conversion Prediction
## Overview
This project focuses on building a machine learning model to predict the likelihood of leads converting into paid customers for ExtraaLearn, an EdTech startup that offers programs on cutting-edge technologies. The goal is to identify which leads are more likely to convert, enabling the company to allocate resources efficiently and optimise marketing strategies. The project includes analysing the lead dataset, building a predictive model, and identifying key factors that influence lead conversion.

## Objective
Predict which leads are more likely to convert to paid customers using machine learning techniques. Identify key factors and variables that contribute to the lead conversion process. Profile the leads that are more likely to convert, helping ExtraaLearn allocate resources more effectively.

## Tools and Techniques
### Programming Language: Python 3.8

### Libraries:
- Data Manipulation: Pandas, NumPy
- Data Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn (Logistic Regression, Decision Trees, Random Forest, XGBoost, etc.)
- Model Evaluation: Confusion Matrix, Precision, Recall, F1 Score

### Techniques:
- Exploratory Data Analysis (EDA)
- Data Preprocessing and Feature Engineering
- Supervised Learning (Classification Models)
- Model Evaluation and Performance Metrics
- Lead Profiling and Insights

## Data Dictionary
The dataset contains information about the leads and their interactions with ExtraaLearn. Below is a summary of the key features:

### Lead Information
- ID: Unique identifier for each lead.
- age: Age of the lead.
- current_occupation: Current occupation of the lead (values: 'Professional', 'Unemployed', 'Student').
- first_interaction: The initial interaction with ExtraaLearn (values: 'Website', 'Mobile App').
- profile_completed: Percentage of profile completed by the lead on the website or mobile app (values: 'Low' (0-50%), 'Medium' (50-75%), 'High' (75-100%)).
- website_visits: Total number of times the lead visited the website.
- time_spent_on_website: Total time spent on the website.
- page_views_per_visit: Average number of pages viewed during website visits.
- last_activity: Last interaction between the lead and ExtraaLearn (values: 'Email Activity', 'Phone Activity', 'Website Activity').

### Media and Referral Information
- print_media_type1: Flag indicating whether the lead has seen the ad in the newspaper.
- print_media_type2: Flag indicating whether the lead has seen the ad in the magazine.
- digital_media: Flag indicating whether the lead has seen the ad on digital platforms.
- educational_channels: Flag indicating whether the lead heard about ExtraaLearn through educational channels (e.g., online forums, educational websites).
- referral: Flag indicating whether the lead heard about ExtraaLearn through referral.

### Outcome Information
- status: Flag indicating whether the lead converted into a paid customer (1 = converted, 0 = not converted).
