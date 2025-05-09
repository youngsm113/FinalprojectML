# Predicting Job Categories and Salaries from LinkedIn Postings
Welcome to the repository for final project: an end-to-end machine learning pipeline that classifies job postings into broad categories and predicts base compensation directly from the posting text and metadata.

## Project Overview
We leverage a dataset of 33,000+ LinkedIn job postings—each containing title, description, company size, view counts, remote flag, and base compensation—to build two supervised models:

## Abstract: 
The research addresses the need to forecast salaries accurately using elements extracted from LinkedIn job postings. A two-day job information collection period produced this dataset containing essential variables, including job titles and descriptions, salaries, and company information. The research employs machine learning methods to reveal connections between the variables and their effects on salary establishment. The research applies two primary machine learning approaches for this evaluation, which include Linear Regression based on Chen et al. (2024) alongside the advanced Gradient Boosting Decision Trees (GBDT) model, which demonstrates superior performance in salary prediction according to Yang (2023). The research targets two main objectives: improving salary estimation approaches while analyzing job market features that affect compensation patterns.
The dataset's extensive features enable thorough investigations into how job characteristics affect salaries. Bao (2024) points out educational attainment and professional experience as essential factors that determine salary levels according to previous research and will be included in the model. The analysis will benefit from ensemble learning techniques and natural language processing methods that address the complexities found in job postings to improve prediction accuracy. A study by Maddi et al. (2024) reviews machine learning uses for detecting deceptive job postings yet supports applying these methods to evaluate job data without specific emphasis on salary forecasts. Mohammed et al. (2023) explores machine learning for job position classification but does not address salary prediction directly. The research aims to enhance knowledge about digital age employment and salary analytics by developing practical tools for employers and job seekers.

## Methodology
The dataset utilized for this analysis comprises job postings collected over a two-day period from LinkedIn, encompassing a rich set of variables including job titles, descriptions, salary estimates, company information, and location. Key preprocessing steps included:
•	Renaming columns for clarity and consistency.
•	Handling missing values and inspecting data types.
•	Categorizing job titles using a custom mapping function that groups similar roles (e.g., “Engineer”, “Manager”, “Nurse”).
•	Exploratory Data Analysis (EDA) using counts and value distributions to understand key job title trends.
Preprocessing techniques included:
•	Label encoding for categorical features.
•	Standard scaling.
•	Handling class imbalance using SMOTE (Synthetic Minority Oversampling Technique).
Machine learning models implemented:
•	TF-IDF and Random Forest Classifier 
•	Gradient Boosting Decision Tree
•	K-Nearest Neighbors (KNN)
•	Linear Regression
For predictive modeling, four machine learning algorithms were employed: Linear Regression, Gradient Boosting Decision Tree, Random Forest and K-Nearest Neighbor. The Linear Regression model serves as a baseline comparison for evaluating more advanced models such as GBDT, which demonstrates enhanced performance in complex salary prediction tasks (Feng et al., 2023). Performance metrics such as Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and R-squared values were employed for evaluation purposes (Matbouli & Alghamdi, 2022).

## Reflection
The analysis underscores the critical value of utilizing machine learning techniques in salary prediction, specifically through the advanced GBDT algorithm. The results provide valuable insights for both job seekers and employers by revealing how job characteristics significantly impact salary establishment. While this research can be used from either perspective- the job seeker or the potential employer, findings and observations were predominantly viewed from the lens of a potential employer to help model strategic decision making in recruiting and compensation planning primarily. Although the findings validate the importance of experience as a vital factor, they also open avenues for further exploration of additional elements that could influence salary dynamics in an evolving job market.
In essence, this project enhances the understanding of digital age employment and salary analytics, contributing valuable tools and frameworks for effective decision-making in hiring and compensation.

## Future Work
Incorporate contextual embeddings (e.g., BERT) for richer text representation
Adjust salaries by geographic cost-of-living indices
Experiment with multi-task models predicting category & salary jointly
Add unsupervised clustering to identify latent job‐specialization groups
