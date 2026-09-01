\# Game Ratings Analytics — Analysis Report


 
\## 1. Project Overview



This project analyzes video game data to understand trends in

game releases and user ratings across genres and platforms.



\## 2. Dataset



The dataset contains 5,000 games and the following columns:



\- Game Name

\- Genre

\- Platform

\- Release Year

\- User Rating



\## 3. Data Cleaning



The following data-cleaning steps were performed:



\- Checked for missing values

\- Checked for duplicate records

\- Identified anomalous values

\- Standardized Genre

\- Standardized Platform

\- Created Decade feature from Release Year



\## 4. Exploratory Data Analysis



The analysis examined:



\- Game releases by genre

\- Game releases by platform

\- User ratings by genre

\- User ratings by platform

\- Rating distribution

\- Rating trends over time

\- Top 5 genres by average rating

\- Top 5 platforms by average rating



\## 5. Statistical Analysis



\### One-Way ANOVA



The hypothesis test was performed to determine whether

user ratings differ significantly across platforms.



\- Significance level: 0.05

\- P-value: approximately 0.758



Since the p-value is greater than 0.05, we fail to reject

the null hypothesis.



Therefore, there is no statistically significant difference

in user ratings across platforms.



\### Correlation Analysis



Pearson correlation was used to examine the relationship

between Release Year and User Rating.



The correlation was approximately 0.0002, indicating

virtually no linear relationship.



\## 6. Predictive Modeling



A Random Forest Regression model was developed to predict

User Rating using:



\- Genre

\- Platform

\- Release Year



\### Model Performance



\- MAE: approximately 2.42

\- RMSE: approximately 2.91

\- R²: approximately -0.253



The model showed poor predictive performance.



\## 7. Feature Selection



Permutation Importance was used to identify the most

influential features.



Feature ranking:



1\. Genre

2\. Release Year

3\. Platform



\## 8. Key Insights



\- Survival had the highest average user rating among genres.

\- PC had the highest average rating among platforms.

\- User ratings remained relatively stable across decades.

\- Platform differences were not statistically significant.

\- Release Year had almost no linear relationship with User Rating.

\- Genre was the strongest predictor among the available features.

\- The available features were insufficient for accurate rating prediction.



\## 9. Recommendations



Future models could include additional variables such as:



\- Sales

\- Critic Score

\- Number of Reviews

\- Developer

\- Publisher

\- Game Budget

\- Playtime

\- User Engagement



These additional variables may improve predictive performance.

