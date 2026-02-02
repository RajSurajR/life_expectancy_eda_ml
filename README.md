# Life Expectancy Analysis (EDA + Machine Learning)

## 📌 Project Overview
This project focuses on analyzing a real-world **Life Expectancy dataset** to understand
the factors that influence life expectancy across different countries.
The work involves **data cleaning, exploratory data analysis (EDA), feature preprocessing**,
and building a **baseline machine learning regression model**.

The objective is not to achieve maximum accuracy, but to demonstrate a **complete and
structured data science workflow** from raw data to model evaluation.

---

## 🎯 Objectives
- Perform data cleaning and preprocessing on a real-world dataset
- Analyze relationships between health, economic, and social factors
- Visualize key patterns and correlations
- Build a baseline regression model to predict life expectancy
- Evaluate model performance using appropriate regression metrics

---

## 🧠 Dataset Description
- Dataset: Life Expectancy Data
- Contains country-level health, economic, and demographic indicators
- Includes both numerical and categorical features
- Target variable: **Life expectancy**

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

---

## 🔍 Project Workflow

### 1️⃣ Data Understanding & Cleaning
- Inspected dataset shape, data types, and summary statistics
- Identified missing values and analyzed their distribution
- Handled missing values using statistical imputation techniques
- Checked for duplicate records
- Separated numerical and categorical features for preprocessing

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed distributions of key numerical features
- Studied correlations between features using a heatmap
- Explored relationships between life expectancy and:
  - Adult mortality
  - GDP
  - Schooling
  - Health-related indicators
- Derived insights to understand which factors may influence life expectancy

---

### 3️⃣ Feature Preprocessing
- Encoded categorical variables
- Prepared feature matrix and target variable
- Performed train-test split to avoid data leakage

---

### 4️⃣ Machine Learning Model
- Built a **baseline regression model** to predict life expectancy
- Model used: Linear Regression
- The model serves as a reference point for understanding feature impact and performance

---

### 5️⃣ Model Evaluation
Evaluated the model using appropriate **regression metrics**:
- **R² Score**
- **Mean Absolute Error (MAE)**

These metrics help assess how well the model explains variance in life expectancy
and the average prediction error.

---

## 📊 Key Learnings
- Real-world datasets often contain missing and inconsistent data
- Exploratory data analysis is critical before model building
- Baseline models provide valuable insights even without advanced tuning
- Interpreting results is as important as building the model itself

---

## 🚀 Future Improvements
- Try non-linear models such as Random Forest or Gradient Boosting
- Perform feature selection to reduce noise
- Apply hyperparameter tuning
- Evaluate model performance using cross-validation

---

## ▶️ How to Run
1. Clone the repository
2. Open the notebook using Jupyter Notebook or Google Colab
3. Run the cells sequentially

---

## 👤 Author
Developed as part of learning and applying **Data Science and Machine Learning fundamentals**.
