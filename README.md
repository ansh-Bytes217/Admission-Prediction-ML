# 🎓 Admission Prediction using Machine Learning

This project aims to predict the probability of a student's admission into a graduate program using machine learning techniques. It uses real-world admission criteria like GRE/TOEFL scores, CGPA, SOP/LOR strength, and research experience to estimate the chance of acceptance.

---

## 📌 Problem Statement

Many students struggle to assess their admission chances and often depend on paid consultants. This project addresses that by providing an automated and accurate way to predict admission chances using ML.

---

## 📊 Dataset Overview

- Source: [Graduate Admission Dataset](https://www.kaggle.com/mohansacharya/graduate-admissions)
- Total records: 500
- Features:
  - **GRE Score** (out of 340)
  - **TOEFL Score** (out of 120)
  - **University Rating** (1 to 5)
  - **SOP Strength** (1 to 5)
  - **LOR Strength** (1 to 5)
  - **CGPA** (out of 10)
  - **Research Experience** (0 or 1)
  - **Chance of Admit** (0 to 1, response variable)

---

## 🧠 Models Used

### 1. **Linear Regression**
- Used both **Ordinary Least Squares (OLS)** and **Gradient Descent**
- Ideal for understanding the linear relationship between inputs and admission chances

### 2. **K-Nearest Neighbors (KNN) Regression**
- Non-parametric model that predicts based on neighborhood similarity
- Achieved higher accuracy compared to linear regression in this dataset

---

## ⚙️ Tools & Technologies

- **Language:** Python  
- **IDE:** Jupyter Notebook  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## 📈 Results

| Model          | Accuracy |
|----------------|----------|
| Linear Regression | 92.71%   |
| KNN Regression     | 99.93%   |

- KNN outperformed Linear Regression in this dataset.
- Accuracy was measured using standard regression metrics (e.g., R² score).

---

## 📌 Techniques Explained

### 🔁 Gradient Descent
- Iteratively updates model coefficients to minimize error
- Learning rate (α) is crucial for convergence

### 📐 Ordinary Least Squares (OLS)
- Fast and memory-efficient
- Uses matrix operations to estimate the best-fitting line

### 🧭 K-Nearest Neighbors
- Predicts by averaging nearby points
- Uses Euclidean distance for similarity

---

## 🚀 How to Run the Project

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/admission-prediction.git
   cd admission-prediction
   
pip install -r requirements.txt

jupyter notebook Admission_Prediction.ipynb

Future Work
Add more features like extracurriculars, essays, etc.

Deploy using Streamlit or Flask

Collect data through student surveys for broader use

🤝 Credits
Dataset: Graduate Admission Dataset on Kaggle

Built by: Ansh Malhotra

