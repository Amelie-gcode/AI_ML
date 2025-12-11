# AI_ML
# HumanForYou: Employee Turnover Analysis & Prediction

## Project Context

**HumanForYou** is a major pharmaceutical company based in India, employing approximately 4,000 people. Despite its size, the company faces a significant challenge: an annual employee turnover rate of around **15%**.

Management has identified that this high attrition rate is detrimental to the company for several reasons:
* **Project Delays:** Departing employees leave projects unfinished, causing delays and damaging the company's reputation with partners and customers.
* **HR Costs:** A large HR department is required solely to manage the recruitment of replacements.
* **Onboarding Efficiency:** New hires require training and time to become fully operational, resulting in lost productivity.

## Objectives

The goal of this project is to use data analysis and machine learning to:
1.  **Identify Factors:** Determine which variables (demographics, job role, satisfaction, etc.) have the greatest influence on employee attrition.
2.  **Predict Turnover:** Build and compare machine learning models to predict whether an employee is likely to leave.
3.  **Propose Improvements:** Provide data-driven recommendations to management to improve retention and employee satisfaction.

## Dataset Description

The data has been provided by the Human Resources department and is anonymized. Each employee is identified by a unique `EmployeeID` across all files.

### Data Sources
* **`general_data.csv`**: Core HR data (demographics, job details).
* **`manager_survey_data.csv`**: Manager feedback on employee performance.
* **`employee_survey_data.csv`**: Employee self-reporting on work quality of life.
* **`in_out_time.zip`**: Time logs for arrival and departure times for the year 2015.

### Data Dictionary

| Variable | Description |
| :--- | :--- |
| **Attrition** | **Target Variable.** Did the employee leave in 2016? (Yes/No) |
| **Age** | Employee age in 2015. |
| **BusinessTravel** | Frequency of work travel (Non-Travel, Rare, Frequent). |
| **DistanceFromHome** | Commute distance in km. |
| **Education** | 1=Pre-college, 2=College, 3=Bachelor, 4=Master, 5=PhD. |
| **JobLevel** | Hierarchical level (1 to 5). |
| **MonthlyIncome** | Gross monthly salary in Rupees. |
| **NumCompaniesWorked** | Companies worked for prior to joining HumanForYou. |
| **PercentSalaryHike** | % salary increase in 2015. |
| **StandardHours** | Contractual hours per day. |
| **StockOptionLevel** | Level of investment in company shares. |
| **TotalWorkingYears** | Total professional experience. |
| **TrainingTimesLastYear** | Number of training days in 2015. |
| **YearsAtCompany** | Seniority at HumanForYou. |
| **YearsSinceLastPromotion** | Years since the last individual promotion. |
| **YearsWithCurrentManager** | Years working under the current manager. |
| **JobInvolvement** | Manager rating: 1 (Low) to 4 (Very High). |
| **PerformanceRating** | Manager rating: 1 (Low) to 4 (Beyond Expectations). |
| **EnvironmentSatisfaction** | Employee rating: 1 (Low) to 4 (Very High). |
| **JobSatisfaction** | Employee rating: 1 (Low) to 4 (Very High). |
| **WorkLifeBalance** | Employee rating: 1 (Poor) to 4 (Excellent). |

*Original Data Source: [Kaggle - HR Analytics Case Study](https://www.kaggle.com/vjchoudhary7/hr-analytics-case-study)*

## 🛠 Methodology

The project follows a structured data science pipeline:

1.  **Data Wrangling & Cleaning:** Handling missing values (`NA`), merging datasets, and processing timestamp data from the attendance logs.
2.  **Exploratory Data Analysis (EDA):** Visualizing distributions and correlations to understand the workforce profile.
3.  **Feature Engineering:** Creating new metrics (e.g., average working hours, overtime frequency) from raw data.
4.  **Modeling:** Testing various algorithms (e.g., Logistic Regression, Random Forest, SVM) to predict Attrition.
5.  **Optimization:** Tuning hyperparameters to improve model performance metrics (Accuracy, Recall, F1-Score).
6.  **Ethical Analysis:** Evaluating the model for bias, fairness, and data privacy compliance.

##  Deliverables

This repository contains the work for the following expected deliverables:

1.  **Jupyter Notebook:** The complete code for analysis, modeling, and results interpretation.
2.  **Ethics Report:** A document detailing the ethical approach, GDPR considerations, and bias mitigation strategies.
3.  **Bibliography:** A list of academic and technical references used to guide the project.
4.  **Presentation:** A summary of the approach, key findings, and final recommendations for the client.

##  How to Run

1.  Clone this repository.
2.  Install the required dependencies (requirements usually include `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
3.  Run the `report.ipynb` notebook.

## 👥 Authors

* **[Amelie Game , Laura MONTANES MOMBIELA , Richard NABADJA, Guillaume HAEBERLE]** - Data Analysis Specialists for HumanForYou.