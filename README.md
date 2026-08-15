# Student Depression Prediction Using Machine Learning

## 📌 Project Overview

This project uses machine learning classification algorithms to predict depression among students based on academic, lifestyle, financial, and mental-health-related factors.

The project includes data preprocessing, exploratory data analysis (EDA), feature encoding/transformation, train-test splitting, training of multiple classification algorithms, and comparison of their performance.

> **Important:** This project is for educational/research purposes only. It is not a medical diagnosis or a substitute for professional mental-health assessment.

## 📂 Files in this Repository

- `student_depression_prediction.ipynb` — Jupyter Notebook containing the complete data analysis, preprocessing, model training, and evaluation workflow.
- `Student_Depression_Dataset.csv` — Dataset used by the notebook.
- `requirements.txt` — Python libraries required to run the notebook.
- `.gitignore` — Files/folders that should not be committed to Git.

## 📊 Dataset

The dataset contains **27,901 records and 18 columns**, including:

- Gender
- Age
- City
- Profession
- Academic Pressure
- Work Pressure
- CGPA
- Study Satisfaction
- Job Satisfaction
- Sleep Duration
- Dietary Habits
- Degree
- Have you ever had suicidal thoughts?
- Work/Study Hours
- Financial Stress
- Family History of Mental Illness
- Depression

## 🔄 Project Workflow

1. Data Loading
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis
5. Categorical Feature Encoding
6. Data Transformation
7. Train-Test Split
8. Machine Learning Model Training
9. Model Evaluation
10. Model Comparison

## 🤖 Machine Learning Algorithms

The notebook evaluates multiple classification algorithms:

- Support Vector Classifier (SVC)
- Gaussian Naive Bayes
- Decision Tree Classifier
- K-Nearest Neighbors
- Random Forest Classifier
- AdaBoost Classifier
- Gradient Boosting Classifier
- Bagging Classifier

## 📈 Model Results

Based on the results already present in the notebook:

| Model | Accuracy |
|---|---:|
| SVC | 84.27% |
| Gaussian Naive Bayes | 65.45% |
| Decision Tree | 76.05% |
| KNN | 71.52% |
| Random Forest | 83.68% |
| AdaBoost | 84.39% |
| Gradient Boosting | **84.46%** |
| Bagging | 81.26% |

Gradient Boosting achieved the highest accuracy among the models evaluated in the current notebook.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
cd Student-Depression-Prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook
```

Then open:

`student_depression_prediction.ipynb`

### 4. Dataset path

Update the dataset-loading cell in the notebook so that it points to:

```python
pd.read_csv("Student_Depression_Dataset.csv")
```

The original notebook currently contains a local Windows path, so this change is required when running it from GitHub on another computer.

## 👩‍💻 Author

**Arpita Dongare**

Student Depression Prediction — Machine Learning Project
