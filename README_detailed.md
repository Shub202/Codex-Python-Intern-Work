# 📊 Data Science & Machine Learning Projects Collection

Welcome to a curated collection of beginner-to-intermediate level **data science and machine learning notebooks**. This repository brings together different domains and tools to solve real-world problems using **Python**, **NumPy**, **Pandas**, **Matplotlib**, **scikit-learn**, and **ipywidgets**.

---

## 📁 Contents Overview

### 1. 🧮 Matrix Operations Tool
An interactive Jupyter Notebook that enables users to perform core matrix operations using widgets. Designed to help learners grasp linear algebra concepts visually.

**Key Features:**
- Dynamically set dimensions for Matrix A and B
- Input matrix values through widgets
- Supported operations:
  - Matrix Addition, Subtraction, Multiplication
  - Transpose of a Matrix
  - Determinant (only for square matrices)
- Clean output rendering for visual feedback

**Use Case:** Educational tool for linear algebra, ideal for math or engineering students.

**Files:**
- `Matrix Operation.py.ipynb`
- `Matrix Operation Output .png` (example result screenshot)

---

### 2. 🎓 Student Data Analysis

This notebook explores student performance data to uncover insights using **data wrangling** and **exploratory data analysis** (EDA).

**Key Features:**
- Load and clean data from `Students.csv`
- Visualize performance metrics: grades, attendance, etc.
- Grouped statistics and filtering using Pandas
- Insightful graphs using Matplotlib or Seaborn

**Use Case:** Useful for understanding how data science can be used in academic analytics.

**Files:**
- `Student_Data_Analysis.ipynb`
- `Students.csv`

---

### 3. 🏠 House Price Prediction Model

A machine learning pipeline that predicts house prices based on historical data. This notebook is structured to reflect real-world ML workflows from preprocessing to model evaluation.

**Key Features:**
- Load and explore housing data (`train.csv`)
- Clean missing data, encode categorical features
- Apply machine learning models like:
  - Linear Regression
  - Decision Trees (if extended)
- Evaluate model with RMSE, MAE

**Use Case:** Great example for beginners learning how to approach regression problems.

**Files:**
- `House prediction.ipynb`
- `train.csv`

---

## 🛠 Setup Instructions

To run these notebooks locally:

1. Clone the repository or extract the ZIP folder
2. Install required Python packages:

```bash
pip install numpy pandas matplotlib scikit-learn ipywidgets
```

3. Enable Jupyter notebook widgets:

```bash
jupyter nbextension enable --py widgetsnbextension --sys-prefix
```

4. Open the notebooks in Jupyter and run all cells.

---

## 🚀 Project Applications

| Notebook                   | Concepts Covered                        | Skills Practiced                    |
|----------------------------|------------------------------------------|-------------------------------------|
| Matrix Operation Tool      | Linear Algebra, NumPy, ipywidgets        | Interactive UIs, Matrix Math        |
| Student Data Analysis      | EDA, Pandas, Matplotlib                  | Data Cleaning, Visualization        |
| House Price Prediction     | Machine Learning, Regression, Modeling   | Preprocessing, Model Evaluation     |

---

## 🧠 Author

This project was created by a data science student combining academic projects and self-learning modules. It aims to demonstrate practical Python applications across math, analytics, and machine learning.

---

## 📃 License

This repository is licensed under the **MIT License**. You’re free to use, modify, and distribute with attribution.

---

## 📌 Recommendation

- For best experience, open the notebooks using **Jupyter Notebook** or **VSCode with Jupyter extension**
