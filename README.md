

This project focuses on predicting income levels using machine learning classification techniques applied to a comprehensive dataset. The dataset includes the following features:
- Age: The age of the individual.
- Workclass: The type of employment (e.g., private, self-employed).
- fnlwgt: Final weight, reflecting the number of people represented by the survey respondent.
- Education: The highest level of education attained.
- Education_num: Numeric representation of education level.
- Marital_status: The marital status of the individual (e.g., single, married).
- Occupation: The job role or type of work the individual is engaged in.
- Relationship: The individual's relationship status (e.g., husband, wife).
- Race: The individual's race.
- Sex: The individual's gender.
- Capital_Gain: Income earned from investments.
- Capital_Loss: Losses incurred from investments.
- Hours_per_week: Number of hours worked per week.
- Native_country: The country of origin.
- Income_level: Target variable indicating income level (e.g., <=50K or >50K).

The project involved several critical steps: data preprocessing, including encoding categorical variables and applying random oversampling to address class imbalances;
data analysis using Seaborn and Matplotlib to explore relationships between features; and feature scaling to normalize the data. 
The dataset was then split into training and testing subsets for model evaluation.
Various classification algorithms were employed, including Logistic Regression, Support Vector Machine (SVM), Decision Trees, Random Forest, and ensemble learning techniques.
Each model was assessed based on its accuracy in predicting income levels, with the most accurate model selected for final training. 
This approach resulted in a robust model capable of effectively classifying income levels based on demographic and employment factors.
