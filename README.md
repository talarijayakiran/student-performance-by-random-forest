# 🎓 Student Performance Prediction — Decision Tree & Random Forest (Capstone Project)

A complete end-to-end machine learning project that predicts whether a student will **pass or fail** based on academic scores and demographic features.  
This repository demonstrates a clean ML workflow used by real ML Engineers and MLOps practitioners — including EDA, preprocessing pipelines, model comparison, and professional reporting.

---

## 📌 Project Objective

The goal of this project is to build a **binary classifier** to predict student performance (Pass/Fail) using:

- 🎯 **Decision Tree Classifier**  
- 🌲 **Random Forest Classifier**

The project focuses on:
- Understanding key academic & demographic factors  
- Comparing tree-based models  
- Visualizing decision boundaries & feature importance  
- Delivering a polished, evaluator-ready PDF report  

---

## 📂 Project Structure

```

student-performance-by-random-forest/
│
├── data/                                   # Dataset (ignored in Git)
│   └── student.csv
│
├── notebooks/
│   └── student_performance.ipynb            # Full ML pipeline notebook
│
├── reports/
│   └── student_performance_premium_report.pdf
│
├── README.md                                # Project documentation
├── requirements.txt                          # Dependencies
└── .gitignore

````

---

## 📊 Dataset Details

**Source:**  
Student Performance Dataset – UCI / Kaggle  
Link: https://www.kaggle.com/datasets/spscientist/students-performance-dataset

**Features include:**
- gender  
- race/ethnicity  
- parental level of education  
- lunch  
- test preparation course  
- math score  
- reading score  
- writing score  

**Target variable created:**  
Pass = 1  
Fail = 0  
(based on average score across 3 exams)

---

## 🔧 End-to-End Workflow

### ✔ 1. Data Loading & Inspection  
Shape, preview, statistics, data types.

### ✔ 2. Exploratory Data Analysis (EDA)  
- Value counts  
- Histograms & distributions  
- Correlation heatmap  
- Score comparison by category  

### ✔ 3. Preprocessing  
Using `ColumnTransformer` + `Pipeline`:
- One-Hot Encoding  
- Scaling numerical features  
- Train/test split (80/20)  

### ✔ 4. Modeling  
Two models built and evaluated:
1. **Decision Tree Classifier**  
2. **Random Forest Classifier**

### ✔ 5. Evaluation Metrics  
For both models:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

### ✔ 6. Visualizations  
- Decision Tree Plot  
- Feature Importance (Random Forest)  
- Metric Comparison Chart  

---

## 🧪 Model Performance (Your Results)

| Model            | Accuracy | Precision | Recall | F1 Score |
|------------------|----------|-----------|--------|----------|
| Decision Tree    | **1.00** | 1.00      | 1.00   | 1.00     |
| Random Forest    | **1.00** | 1.00      | 1.00   | 1.00     |

⚠️ **Note:**  
Perfect scores may indicate a simple dataset or highly separable features — addressed in the PDF report.

---

## 📬 Key Insights

- Academic scores (math, reading, writing) dominate prediction power  
- Decision Tree offers full interpretability  
- Random Forest provides more robust feature importance  
- Very strong model performance due to dataset separability  

---

##  How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/talarijayakiran/student-performance-by-random-forest.git
cd student-performance-by-random-forest
````

### 2. Create virtual environment

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:
`notebooks/student_performance.ipynb`

---

## 📄 Report

A polished, evaluator-ready 2–3 page PDF report is available here:
👉 `reports/student_performance_premium_report.pdf`

Includes:

* Dataset summary
* Model explanations
* Feature importance
* Metric comparison
* Professional insights

---

## 📚 References

* UCI Machine Learning Repository
* Kaggle Student Performance Dataset
* Scikit-Learn Documentation
* Matplotlib & Seaborn

---

## 👤 Author

**Talari Jaya Kiran**
MLOps / Machine Learning Engineer
GitHub: [https://github.com/talarijayakiran](https://github.com/talarijayakiran)

r download the project folder  
2. Create a virtual environment:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate
