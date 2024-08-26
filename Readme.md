**Waze User Churn Analysis Project (Google Advanced Data Analytics Certificate)**

This repository contains the data, scripts, and results for the Waze User Churn Analysis Project. The goal of this project is to analyze user behavior in the Waze app to understand the factors contributing to monthly user churn and develop models to predict churn. This analysis is important for guiding strategies to improve user retention and overall app growth.

**Project Overview**

The Waze data team has worked on a comprehensive data analytics project focused on reducing monthly user churn. Churn is defined as users who either uninstall the Waze app or stop using it. This project uses data analytics and machine learning to identify key factors associated with user churn and predict which users will likely churn.

**Key Milestones:**

- Milestone 1: Preliminary Data Summary. Investigated user data to identify relationships between variables.
    - Key Insight: Churned users typically had more drives in the last month than retained users, but they drove fewer days with longer trips in both distance and duration.

- Milestone 2: Exploratory Data Analysis (EDA). Discovered patterns indicating that users who engage more frequently with the app are less likely to churn.
   - Key Insight: Higher churn rates are observed among users who didn't use the app much last month.

- Milestone 3: Two-sample Hypothesis Testing. Conducted a hypothesis test to compare user behavior between Android and iPhone users.
   - Key Insight: No statistically significant difference was found between the mean number of drives for iPhone and Android users.

- Milestone 4: Binomial Logistic Regression Modeling. Developed a binomial logistic regression model to predict user churn.
    - Key Insight: The model highlighted activity days as the most important feature negatively correlated with churn. However, the model had low recall, indicating it missed many users who would churn.

- Milestone 6: Machine Learning Model Development. Developed and compared Random Forest and XGBoost models.
     - Key Insight: The XGBoost model outperformed the logistic regression model, with better recall and precision scores, but it highlighted the need for additional data to improve prediction accuracy.


---

## Repository Structure

- **`data/`**  
  This directory includes a dataset that was used throughout the analysis.

- **`notebooks/`**  
  Here, you will find Jupyter notebooks that contain the steps for data exploration, analysis, and model development.

- **`executive summary/`**  
  This folder has the reports that summarize key findings from each project milestone.

- **`models/`**  
  Saved machine learning models are stored in this directory, including those developed in the model training phase.

---

