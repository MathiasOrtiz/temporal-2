# 🩺 Diabetes Prediction: Random Forest and XGBoost

## 📖 Description
This project involves analyzing the **Diabetes Dataset** to predict whether a person is diabetic based on specific medical metrics. The dataset includes health indicators like glucose levels, BMI, and blood pressure, sourced from the **Pima Indian Diabetes Dataset**. The analysis includes data cleaning, visualization, and predictive modeling using **Random Forest** and **XGBoost**.

---

## 🚀 Objectives
- Preprocess and clean the dataset by handling missing values and outliers.
- Explore relationships between variables using statistical methods and visualizations.
- Implement and evaluate classification models:
  - **Random Forest**
  - **XGBoost**
- Optimize model performance using hyperparameter tuning and cross-validation.

---

## 📊 Key Steps
1. **Data Cleaning**:
   - Removed outliers (e.g., blood pressure and glucose values of `0`).
   - Ensured no duplicates or null values in the dataset.

2. **Exploratory Data Analysis**:
   - Histogram and boxplot visualizations for feature distributions.
   - Heatmaps to identify correlations, e.g., glucose levels had the highest correlation (49%) with diabetes outcomes.

3. **Model Implementation**:
   - Models implemented:
     - **Random Forest**: Accuracy of 79%, AUC of 0.85.
     - **XGBoost**: Accuracy of 74%, AUC of 0.87 after tuning.
   - Used pipelines for seamless preprocessing and modeling.

4. **Hyperparameter Tuning**:
   - Improved XGBoost performance to achieve the best AUC of 0.87.

---

## 🚀 Technologies Used
This project leverages the following tools and technologies:
- **Python**: For all computations and modeling.
- **Jupyter Notebook**: For interactive data exploration.
- **Libraries**:
  - Pandas & NumPy: Data manipulation and preprocessing.
  - Scikit-learn: Classification models and evaluation metrics.
  - XGBoost: Gradient boosting implementation.
  - Matplotlib & Seaborn: Data visualization.

---

## 📈 Results
- **Random Forest (Initial)**:
  - Accuracy: 79%
  - AUC: 0.85
- **XGBoost (Tuned)**:
  - Accuracy: 79%
  - AUC: 0.87
- The **tuned XGBoost model** demonstrated the best performance, making it the most suitable for this dataset.
