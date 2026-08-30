# Applied Machine Learning & Statistical Data Mining

This repository contains a collection of statistical learning models, predictive analytics, and data mining workflows applied to business, financial, socio-economic, and operational domain datasets. Each project addresses a distinct decision-making task using rigorous exploratory data analysis (EDA), statistical modeling, feature engineering, and model evaluation.

---

## 📌 Repository Overview & File Analysis

| File Name | Domain / Focus | Key Methodologies & Techniques | Primary Objectives |
| :--- | :--- | :--- | :--- |
| **`AccountingFraud_Logistic_Regression.ipynb`** | Forensic Accounting & Fraud Detection | Binary Logistic Regression, Odds Ratios, Feature Selection, Confusion Matrix Evaluation | Detect indicators of financial misstatement and corporate accounting fraud using key financial performance metrics. |
| **`Bank.ipynb`** | Retail Banking & Financial Services | Supervised Classification, Customer Segmentation, Imbalanced Class Handling | Predict customer subscription to term deposits based on telemarketing history and demographic attributes. |
| **`CarSeat.ipynb`** | Retail Analytics & Sales Strategy | Decision Trees, Feature Importance Analysis, Tree Pruning | Model factors driving child car seat sales across retail locations to optimize distribution and marketing budgets. |
| **`Employee_Attrition.ipynb`** | HR Analytics & Talent Retention | Logistic Regression, Decision Trees, Feature Engineering, Metric Evaluation (Recall/Precision) | Identify major risk drivers behind employee turnover and build predictive models for voluntary resignation. |
| **`Immigration.ipynb`** | Demographics & Policy Analysis | Time-Series Trends, Data Wrangling, Descriptive Aggregations | Analyze migration patterns, temporal shifts, and demographic trends across international borders. |
| **`Kiva_Analysis.ipynb`** | Microfinance & Social Impact | Exploratory Data Analysis, Non-Profit Lending Metrics, Demographic Clustering | Assess funding success factors, loan amounts, and borrower demographics for microfinance initiatives globally. |
| **`LDA,_QDA,_NB_and_KNN_Student.ipynb`** | Comparative Statistical Learning | Linear Discriminant Analysis (LDA), Quadratic Discriminant Analysis (QDA), Naïve Bayes, $K$-Nearest Neighbors ($K$-NN) | Compare generative vs. non-parametric classifiers on multi-class decision boundaries to evaluate model performance trade-offs. |
| **`Life.ipynb`** | Global Health & Socio-Economics | Regression Modeling, Multicollinearity Diagnostics, Hypothesis Testing | Identify key health, socio-economic, and lifestyle determinants influencing global life expectancy. |
| **`Linear_Regression.ipynb`** | Statistical Inference & Regression | Ordinary Least Squares (OLS), Residual Analysis, Homoscedasticity Checks, Coefficient Interpretation | Establish foundational linear regression workflows with model diagnostic testing and variance analysis. |
| **`Logistic_Regression.ipynb`** | Binary Classification Frameworks | Maximum Likelihood Estimation, ROC-AUC, Precision-Recall Curves | Demonstrate fundamental binary classification pipelines, log-odds interpretation, and decision threshold tuning. |
| **`Order_and_user_data_analysis.ipynb`** | E-Commerce & Consumer Behavior | User Cohort Analysis, Order Frequency Aggregations, Behavioral Segmentation | Analyze customer purchasing patterns, order volume distributions, and user lifecycle dynamics. |
| **`Tariff.ipynb`** | International Trade & Policy | Econometric Modeling, Impact Evaluation, Multivariate Analysis | Quantify the impact of trade tariffs and policy shifts on trade volume, pricing, and economic activity. |
| **`TelcoChurn.ipynb`** | Telecommunications & Retention | Class Imbalance Handling, Feature Importance Scoring, Ensemble Classifiers | Build predictive customer churn models to identify high-risk subscribers and formulate retention strategies. |
| **`ToyotaCorola.ipynb`** | Automotive Pricing & Valuation | Multiple Linear Regression, Feature Selection (Stepwise/LASSO), Model Evaluation (RMSE, $R^2$) | Predict secondary market valuation of used vehicles based on mileage, age, fuel type, and technical specifications. |

---

## 🔬 Core Methodologies

* **Parametric & Non-Parametric Modeling:** OLS Regression, Binary/Multinomial Logistic Regression, Linear & Quadratic Discriminant Analysis (LDA/QDA).
* **Machine Learning Classifiers:** Decision Trees, $K$-Nearest Neighbors ($K$-NN), Naïve Bayes.
* **Model Diagnostics & Evaluation:** ROC-AUC, Confusion Matrices, RMSE, $R^2$, Residual Plots, Multicollinearity (VIF) Assessment.
* **Data Processing & Analytics:** Feature Engineering, Handling Missing Data, Class Imbalance Mitigation, Cohort Analysis.

---

## 🛠️ Environment Setup & Reproducibility

### Dependencies
To run these notebooks locally, ensure you have Python 3.8+ installed along with the required libraries:

```bash
git clone [https://github.com/sibangi-git/Data_Mining.git](https://github.com/sibangi-git/Data_Mining.git)
cd Data_Mining
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels jupyter

```

### Execution

Launch Jupyter Notebook to view and execute any individual project notebook:

```bash
jupyter notebook

```
