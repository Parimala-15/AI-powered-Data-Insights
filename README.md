# AI-powered-Data-Insights Internship at Excelerate.

Internship Work Summary
As part of the AI-Powered Data Insights Virtual Internship at Excelerate, I worked on a comprehensive real-world project aimed at improving student retention through data analysis, predictive modeling, and intelligent recommendations. Below is a detailed overview of the work I accomplished:

1. Dataset Understanding & Cleaning
*Explored learner engagement data from the SLU Opportunity Wise Dataset
*Cleaned and standardized fields including signup dates, birth dates, apply dates, and status codes
*Handled missing values, standardized categorical fields, and removed logical inconsistencies
*Applied IQR-based filtering to detect and address outliers in engagement and completion time

🛠 2. Feature Engineering
Created derived features like:

*Age, Opportunity Duration, Engagement Lag, and Completion Time
*Application Timing (binary flag for early vs late applications)
*Signup Month/Day to analyze seasonality
*Engagement Score as a weighted composite of key metrics
*Interaction Features such as Age × Opportunity Duration
*Normalized numerical features using MinMaxScaler
*One-hot encoded categorical features for machine learning compatibility

📊 3. Exploratory Data Analysis (EDA)
Visualized key trends using:

*Line Charts for monthly sign-up and completion trends
*Heatmaps for seasonal signup patterns and status distribution
*Box Plots and Histograms for engagement and completion time
*Funnel Charts to track user journey (Signup → Engagement → Completion)
*Scatter Plots to assess influence of demographics on engagement
*Geo Heatmaps to show global learner distribution
*Analyzed outliers, low-activity days, demographic clusters, and engagement behavior by status

🤖  4. Predictive Modeling
*Defined target variable DroppedOut based on status codes
*Performed data splitting (train/test) with stratified sampling
*Trained and evaluated 8 machine learning classifiers:
*Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, AdaBoost, SVM, KNN, Naive Bayes
*Achieved best performance using Random Forest:

Accuracy: 96%, F1 Score: 96%

Identified Engagement Score, Application Timing, and Completion Time as top predictors

💡 5. Churn Analysis
*Investigated dropout trends using:
*Churn rate formulas and time-based dropoff visualization
*Feature importance from models to determine causes
*Behavioral segmentation based on age, engagement score, and opportunity type

Revealed key risk factors:
Low engagement (<40), delayed completions (>280 days), late applications, and age extremes

🧠 6. Rule-Based Recommendation System
Developed a configurable, rule-based engine to suggest personalized interventions

Used conditions based on:

Engagement Score, Age, Completion Time, Application Timing, Major, Status Code

Sample recommendations included:

🎮 Gamified micro-courses for young, low-engagement learners
👩‍🏫 Mentorship for older learners
📣 Re-engagement emails for churned users
🎓 Career webinars for those with disengagement in specific majors

Implemented rules via recommend_interventions() and exported output to CSV

📂 Deliverables
✅ Cleaned and engineered dataset
✅ Full predictive modeling notebook (with visualizations and model performance metrics)
✅ Rule-based recommendation CSV (student_recommendations_new_columns.csv)
✅ Final report PDF summarizing methodology, analysis, results, and insights

This internship allowed me to gain hands-on experience in the full data science lifecycle—from raw data to actionable AI-powered insights—while working in a collaborative, impact-driven environment.



