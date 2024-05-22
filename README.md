# H1N1-Vaccine-Phase-3-Project
Background:
Vaccination is a key public health measure to fight infectious diseases. Vaccines provide immunization for individuals and enough vaccination in a community can reduce further spread of a diseases through herd immunity.
Objectives
1. Predict Vaccination Uptake Based on Demographic and Socioeconomic Factors:
Objective: Identify the strongest predictors of H1N1 vaccination uptake using demographic (age, gender, race) and socioeconomic (income, education level) data.
Purpose: Focus public health efforts on demographic groups with lower predicted vaccination rates to enhance targeted outreach and intervention programs.
2. Forecast Future Vaccination Rates:
Objective: Use current vaccination rates and demographic data to predict future vaccination trends for H1N1.
Purpose: Ensure adequate planning for vaccine supply and distribution by forecasting areas and populations that may require more resources or targeted campaigns.
3. Analyze the Impact of Public Perceptions on Vaccination Behavior:
Objective: Assess how respondents' perceptions of illness risks and vaccine effectiveness predict their likelihood of getting vaccinated.
Purpose: Develop and refine public health messaging to address specific misconceptions and improve overall vaccination rates by tailoring communication strategies to public concerns.
4. Evaluate the Effectiveness of Preventive Behaviors on Vaccination Rates:
Objective: Predict how various preventive behaviors (e.g., handwashing, avoiding crowds) correlate with vaccination status and uptake.

DATA PREPARATION
The data was loaded and appropriately cleaned.

The variable of interest in H1N1 vaccine

EXPLORATORY DATA ANALYSIS
Univariate analysis showed a class imbalance problem with a majority negative responses (class 0)

Bivariate analysis was also done showing the varying distributions for those who reported positive response (class 1) h1n1 vaccine

Multivariate analysis shown below using the correlation heatmap
![image](https://github.com/FelixMburu/H1N1-Vaccine-Phase-3-Project/assets/151352303/ea8988d4-19f0-4ece-9d98-5d28f77940b2)

SMOTE was performed to correct the class imbalance problem
Modeling was performed using
1. Logistic regression
2. Decision trees
3. K Nearest Neighbor
4. XGboost

These models were tuned using hyperparameter tuning to improve model performance
XGboost showed best model performance
6. 
