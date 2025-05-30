# AI-powered-Data-Insights Internship at Excelerate.

### 📌 Internship Work Summary

As part of the **AI-Powered Data Insights Virtual Internship at Excelerate**, I worked on a comprehensive real-world project aimed at improving student retention through data analysis, predictive modeling, and intelligent recommendations. Here's a detailed summary of the work I accomplished:

---

#### 🔍 1. Dataset Understanding & Cleaning
- Explored learner engagement data from the **SLU Opportunity Wise Dataset**
- Cleaned and standardized fields including **signup dates, birth dates, apply dates, and status codes**
- Handled missing values, standardized categorical fields, and removed logical inconsistencies
- Applied **IQR-based filtering** to detect and handle outliers in engagement and completion time

---

#### 🛠 2. Feature Engineering
- Created new derived features such as:
  - **Age**
  - **Opportunity Duration**
  - **Engagement Lag**
  - **Completion Time**
  - **Application Timing** (early vs late)
  - **Signup Month/Day**
  - **Interaction Features** (e.g., Age × Opportunity Duration)
- Built a composite **Engagement Score**
- Normalized features using **MinMaxScaler**
- One-hot encoded categorical variables for ML compatibility

---

#### 📊 3. Exploratory Data Analysis (EDA)
- Visualized key patterns and behaviors using:
  - **Line Charts** for monthly sign-up and completion
  - **Heatmaps** for seasonality and opportunity-status relationship
  - **Box Plots** and **Histograms** for completion time and engagement score
  - **Funnel Charts** to analyze user flow (Signup → Engagement → Completion)
  - **Scatter Plots** for age, gender, and engagement comparisons
  - **Geo Heatmaps** to display global learner distribution
- Identified outliers, low-activity days, engagement gaps, and demographic insights

---

#### 🤖 4. Predictive Modeling
- Defined binary churn variable `DroppedOut` using engagement status codes
- Applied train-test split with stratified sampling
- Trained and evaluated multiple ML models:
  - **Logistic Regression**
  - **Decision Tree**
  - **Random Forest** ✅ *(Best performer: 96% Accuracy & F1 Score)*
  - **Gradient Boosting**
  - **AdaBoost**
  - **SVM, KNN, Naive Bayes**
- Identified **Engagement Score**, **Application Timing**, and **Completion Time** as top churn predictors

---

#### 💡 5. Churn Analysis
- Computed churn rate and tracked early-stage dropout patterns
- Analyzed behavioral factors contributing to churn:
  - **Low engagement (<40)**
  - **Prolonged completion time (>280 days)**
  - **Late applications**
  - **Age extremes (≤14 or >40)**
- Derived actionable insights to support early intervention strategies

---

#### 🧠 6. Rule-Based Recommendation System
- Developed a rule-based recommender system with configurable thresholds
- Designed intervention logic based on:
  - **Engagement Score, Age, Completion Time, Application Timing, Major, Status**
- Implemented conditions using a custom `recommend_interventions()` function
- Example recommendations:
  - 🎮 Gamified micro-courses for young learners with low engagement
  - 👩‍🏫 Mentorship for older students
  - 📣 Re-engagement emails for dropped or withdrawn users
  - 🎓 Career webinars aligned with major categories
- Output exported to `student_recommendations_new_columns.csv`

---

#### 📂 Deliverables
- ✅ Cleaned dataset and feature-engineered dataframe
- ✅ Full predictive modeling notebook with evaluation metrics
- ✅ EDA visualizations covering trends, churn, engagement, and demographics
- ✅ Rule-based recommender output file (CSV)
- ✅ Final PDF report documenting the methodology, analysis, and outcomes

---

This internship strengthened my skills in **data wrangling, statistical analysis, machine learning, and AI-driven recommendations**, and offered real-world experience in transforming raw data into strategic, actionable insights for educational impact.

