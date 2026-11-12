# EduPredict-AI


# 🎓 EduPredict AI – Student Performance Prediction System

## 📌 Project Overview

EduPredict AI is a Machine Learning-based student performance prediction system developed using Python and Google Colab. It analyzes student academic records, study habits, attendance, and other educational factors to predict final mathematics examination grades.

The project uses multiple Machine Learning regression algorithms to compare prediction performance and identify the best-performing model based on evaluation metrics.

## 🎯 Objectives

- Predict students' final academic performance using Machine Learning.
- Analyze the relationship between study habits and academic grades.
- Compare different regression algorithms.
- Evaluate model performance using standard evaluation metrics.
- Generate data visualizations to understand student performance patterns.
- Explore data-driven insights that can support better learning strategies.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Google Colab | Development environment |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning |
| UCI Repository | Dataset source |

## 📊 Dataset Information

**Dataset:** Student Performance Dataset

**Source:** UCI Machine Learning Repository

Dataset Link: https://archive.ics.uci.edu/dataset/320/student+performance

The project uses the Mathematics student performance dataset (`student-mat.csv`).

- Total student records: 395
- Total columns: 33
- Target variable: G3 (Final Grade)

### Selected Features

| Feature | Description |
|---|---|
| studytime | Weekly study time |
| absences | Number of absences |
| failures | Previous class failures |
| G1 | First-period grade |
| G2 | Second-period grade |
| age | Student age |
| Medu | Mother's education |
| Fedu | Father's education |
| goout | Going-out frequency |
| health | Health status |

## ⚙️ Project Workflow

1. Dataset Collection – Downloaded student performance data from UCI.
2. Data Exploration – Examined records, columns, data types, and statistics.
3. Data Preprocessing – Checked missing values and duplicate records.
4. Feature Selection – Selected relevant input features and target variable.
5. Exploratory Data Analysis – Created charts and correlation heatmaps.
6. Data Splitting – Divided data into 80% training and 20% testing.
7. Feature Scaling – Applied StandardScaler for Linear Regression.
8. Model Training – Trained three regression algorithms.
9. Model Evaluation – Compared performance using MAE, RMSE, and R².
10. Prediction Analysis – Compared actual and predicted student grades.

## 🤖 Machine Learning Algorithms

### 1. Linear Regression
Predicts final student grades by learning relationships between input features and target values.

### 2. Decision Tree Regressor
Uses decision rules and branching structures to predict academic performance.

### 3. Random Forest Regressor
Combines multiple decision trees to generate numerical predictions.

## 📈 Model Evaluation Metrics

The models are evaluated using:

- **MAE (Mean Absolute Error):** Measures average absolute prediction error.
- **RMSE (Root Mean Squared Error):** Measures prediction error while penalizing larger errors.
- **R² Score:** Measures how much variation in the target is explained by the model.

The model with the lowest test RMSE is selected for the initial comparison.

## 📉 Visualizations

The project includes:

- Student Study Time Distribution
- Final Grade Distribution
- Study Time vs Final Grade
- Correlation Heatmap
- Machine Learning Model Comparison
- Actual vs Predicted Grades

## 💻 How to Run the Project

### Step 1: Open Google Colab

https://colab.research.google.com/

### Step 2: Open the Project Notebook

Upload or open `EduPredict_AI_Final_Project.ipynb`.

### Step 3: Install Dependencies

```python
!pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 4: Execute the Notebook

Run all cells in sequence, from dataset download and preprocessing through model training and evaluation.

## 📁 Project Structure

```text
EduPredict-AI/
│
├── EduPredict_AI_Final_Project.ipynb
├── README.md
└── student_performance.zip
```

The dataset ZIP can also be downloaded directly by running the notebook's download cell.

## 🔮 Future Enhancements

- Develop an interactive student prediction web application using Gradio or Streamlit.
- Add personalized study recommendations.
- Introduce more academic and behavioral features.
- Improve model performance through hyperparameter tuning.
- Deploy the application online.
- Add student performance reports and visual analytics.

## ⚠️ Limitations

- Predictions are based on the selected UCI mathematics dataset.
- The dataset contains information from a particular educational context.
- Previous grades (G1 and G2) are included as input features, so predictions rely partly on earlier academic performance.
- Predictions are estimates and should not be treated as guaranteed examination results.

## 👩‍💻 Author

**Sri Devi Chundru**

AI & Data Science Student

GitHub: https://github.com/chsridevi03

## 📜 Acknowledgement

Thanks to the UCI Machine Learning Repository for providing the Student Performance Dataset and to the open-source Python community for the libraries used in this project.

---

⭐ If you find this project interesting, consider giving the repository a star!

**Project:** EduPredict AI – Student Performance Prediction System

**Domain:** Artificial Intelligence & Machine Learning
