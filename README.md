# 📘 Data Science Tasks Summary

## Task 1: Exploring and Visualizing a Simple Dataset

### 📌 Objective
Explore and visualize a dataset to understand feature distributions and relationships.

### 🧠 Approach
- Loaded the Iris dataset using seaborn.
- Displayed basic data insights like head, shape, and columns.
- Visualized relationships using scatter plots, histograms, and boxplots.

### 📊 Results and Insights
- Found clear separation between species based on petal length and width.
- Detected outliers using boxplots.
- Visual insights support the separability of classes.

---

## Task 2: Data Cleaning and Preprocessing

### 📌 Objective
Perform data cleaning, handle missing values, and prepare data for modeling.

### 🧠 Approach
- Identified missing values using `isnull().sum()`.
- Imputed missing values using mean, median, or mode based on column type.
- Handled duplicates and ensured data consistency.

### 📊 Results and Insights
- Cleaned data leads to improved model stability.
- Proper imputation preserves overall data distribution.

---

## Task 3: Feature Engineering

### 📌 Objective
Create new features and transform existing ones to improve model performance.

### 🧠 Approach
- Generated interaction features and polynomial terms.
- Normalized numerical features using standardization.
- Encoded categorical variables using one-hot encoding.

### 📊 Results and Insights
- Feature scaling improved convergence of models.
- New interaction terms provided better representation of relationships.

---

## Task 4: Model Building and Evaluation

### 📌 Objective
Build classification models and evaluate performance using various metrics.

### 🧠 Approach
- Trained classifiers like Logistic Regression and Decision Tree.
- Used accuracy, precision, recall, and F1-score for evaluation.
- Performed train-test split with reproducibility using random seed.

### 📊 Results and Insights
- Logistic Regression performed well with balanced features.
- Decision Trees gave interpretable rules and revealed important features.

---

## Task 5: Personal Loan Acceptance Prediction

### 📌 Objective
Predict which customers are likely to accept a personal loan offer.

### 🧠 Approach
- Loaded the Bank Marketing Dataset using pandas with semicolon delimiter.
- Performed EDA on `age`, `job`, and `marital` status.
- Encoded data and trained Logistic Regression and Decision Tree.
- Evaluated models using confusion matrix and classification report.

### 📊 Results and Insights
- Younger individuals and those with previous successful contacts were more likely to accept loans.
- Decision Tree revealed key features like `poutcome`, `month`, and `job`.
- Logistic regression confirmed similar top features.

---

