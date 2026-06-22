# 💼 Salary Prediction using Linear Regression

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

<p align="center">
  A machine learning project that predicts employee salary based on years of experience using Linear Regression.
</p>

---

## 📌 Project Overview

This project builds a **Simple Linear Regression** model to predict an employee's salary from their years of professional experience. It walks through the complete ML pipeline — from data loading and exploratory analysis to model training, evaluation, and visualization.

> **Use case:** HR teams, job seekers, and analysts can use this model to estimate fair compensation based on experience level.

---

## 📂 Dataset

| Feature | Description |
|---|---|
| `YearsExperience` | Number of years of professional experience (input feature) |
| `Salary` | Annual salary in USD (target variable) |

- **Source:** `Salary Data.csv`
- **Split:** 80% Training / 20% Testing

---

## 🔍 Project Workflow

```
1. Import Libraries
       ↓
2. Load Dataset
       ↓
3. Exploratory Data Analysis (EDA)
       ↓
4. Data Preprocessing & Train-Test Split
       ↓
5. Train Linear Regression Model
       ↓
6. Evaluate & Visualize Results
```

---

## 📊 Exploratory Data Analysis

The EDA phase covers:

- Previewing the first and last 5 rows of the dataset
- Checking dataset shape, data types, and null values via `df.info()`
- Generating a statistical summary with `df.describe()`
- Visualizing the relationship between **YearsExperience** and **Salary** using a scatter plot

---

## 🤖 Model Details

| Parameter | Value |
|---|---|
| Algorithm | Linear Regression (Scikit-Learn) |
| Feature | `YearsExperience` |
| Target | `Salary` |
| Test Size | 20% |
| Random State | 42 |

The trained model learns:

```
Salary = (Coefficient × YearsExperience) + Intercept
```

---

## 📈 Results

- **R² Score** calculated on the full dataset to measure model accuracy
- Actual vs. Predicted salary comparison table generated for test data
- Regression line plotted over the original scatter data for visual validation

**Example Prediction:**
```python
lreg.predict([[16]])  # Predicts salary for 16 years of experience
```

---

## 🧰 Tech Stack

| Library | Purpose |
|---|---|
| `numpy` | Numerical operations |
| `pandas` | Data manipulation and analysis |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical data visualization |
| `scikit-learn` | Machine learning model |

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/salary-prediction.git
   cd salary-prediction
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook SundasNaseem_salary_prediction_.ipynb
   ```

3. Place `Salary Data.csv` in the same directory (or update the path in the notebook).

4. Run all cells in order.

---

## 📁 Repository Structure

```
salary-prediction/
│
├── SundasNaseem_salary_prediction_.ipynb   # Main Jupyter Notebook
├── Salary Data.csv                          # Dataset
└── README.md                                # Project documentation
```

---

## 👩‍💻 Author

**Sundas Naseem**

<p>
  <a href="https://github.com/your-username">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/your-profile">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
</p>

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

<p align="center">⭐ If you found this project helpful, consider giving it a star!</p>
