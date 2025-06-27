# 🚀 Titanic Dataset – AIML Internship Assignment

This repository contains two core tasks completed as part of the AIML internship, using Python and Google Colab for data analysis and modeling on the Titanic dataset.

---

## 📘 Task 1: Data Wrangling, Preprocessing, and Modeling

### 🔍 Step-by-Step Process

1. **Data Exploration**
   - Loaded the dataset using `pandas`
   - Viewed structure, data types, and missing values
   - Used `.info()` and `.describe()` for basic profiling

2. **Handling Missing Values**
   - Imputed missing `Age` with **median**
   - Filled `Embarked` using **mode**
   - Dropped `Cabin` column (too many nulls)
   - Dropped rows missing `Survived`

3. **Categorical Encoding**
   - Converted `Sex` using label encoding (male → 0, female → 1)
   - Applied one-hot encoding to `Embarked`

4. **Feature Scaling**
   - Scaled `Age` and `Fare` using `StandardScaler`

5. **Outlier Detection and Removal**
   - Used boxplots to identify outliers
   - Removed outliers using IQR method

6. **Correlation Analysis**
   - Heatmap of feature correlations

7. **Train/Test Split**
   - Removed unneeded columns: `Name`, `Ticket`, `PassengerId`
   - Split into training and testing sets

8. **Modeling**
   - Trained a Logistic Regression model
   - Evaluated with:
     - Accuracy
     - Confusion Matrix
     - Classification Report

9. **Model Comparison (Optional)**
   - Tried additional models:
     - `RandomForestClassifier`
     - `SVC`
     - `XGBClassifier`

---

### 📊 Technologies Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Google Colab

---

## 📘 Task 2: Exploratory Data Analysis (EDA) and Visualization

🔗 **Notebook File:** [Task-2-AIML.ipynb](Task_2_AIML.ipynb)

This notebook focuses on **feature-level analysis, patterns, and trends** using visualization.

### ✅ Task Objectives

1. **Generate Summary Statistics**
   - Calculated mean, median, standard deviation, and quartiles

2. **Create Histograms & Boxplots**
   - Used histograms for distribution shapes
   - Used boxplots to detect outliers

3. **Explore Feature Relationships**
   - Visualized correlation matrix
   - Created pairplots with `hue="Survived"` to observe relationships

4. **Identify Patterns, Trends, Anomalies**
   - Found survival trends based on:
     - Gender (female > male)
     - Class (1st > 3rd)
     - Fare and age (younger/high-fare had better survival)

5. **Feature-Level Inferences**
   - Gender, Pclass, and Fare are strong predictors
   - Traveling alone or in small families affected outcomes

---

### 📈 How to Run

1. Open `Task-2-AIML.ipynb` in Google Colab
2. Upload the dataset: `Titanic-Dataset.csv`
3. Run all cells from top to bottom
4. View visualizations and inferences

---

## 📂 Files in This Repository

| File | Description |
|------|-------------|
| `Task_1_AIML.ipynb` | Titanic data wrangling, modeling, classification |
| `Task-2-AIML.ipynb` | Titanic data EDA, visualization, and feature insights |
| `Titanic-Dataset.csv` | CSV dataset (if included) |
| `README.md` | Documentation for internship tasks |

---
## 🏠 Housing Regression Notebook  
**File**: `Task3_new_AIML.ipynb`  
**Contents**:  
- Data loading & preprocessing  
- Simple & multiple linear regression  
- Model evaluation (MAE, MSE, R²)  
- Visualizations (coefficients, actual vs predicted)  
- Bonus: Regularization and feature selection

## 👨‍💻 Author
This repository was created as part of an **AI/ML Internship Assignment**, focused on hands-on application of data preprocessing, visualization, and machine learning.
