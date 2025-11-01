# 🎓 Student Performance Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

Predicting students' academic performance using Linear Regression.

---

## 📝 Description

This project analyzes student data to predict final grades using **Linear Regression**. By examining various academic and behavioral factors, the model identifies key patterns that influence student performance and provides actionable insights for academic improvement.

---

## 📊 Dataset

The dataset (`Student_Performance.csv`) contains the following features:

| Feature | Description |
|---------|-------------|
| **Hours Studied** | Time spent studying |
| **Previous Scores** | Past exam results |
| **Extracurricular Activities** | Participation in non-academic activities |
| **Sleep Hours** | Average daily sleep duration |
| **Sample Question Papers Practiced** | Number of practice papers completed |
| **Target** | Final performance score (prediction target) |

**Dataset Location:** `data/Student_Performance.csv`

---

## 🚀 Installation & Usage

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run the Project
```bash
# Start Jupyter Notebook
jupyter notebook

# Then open student.ipynb in your browser
```

**Or run all cells directly:**
```bash
jupyter nbconvert --to notebook --execute student.ipynb
```

---

## 📈 Results

### Model Performance

| Metric | Value |
|--------|-------|
| **Mean Squared Error (MSE)** | 4.24 |
| **Root Mean Squared Error (RMSE)** | 2.06 |
| **R-squared (R²)** | 0.9884 |

> **Note:** The model achieves **98.84% accuracy**, indicating excellent predictive performance.

### Visualization

![Predicted vs Actual Scores](images/output.png)

*The scatter plot shows the strong correlation between predicted and actual scores, with most points closely aligned to the ideal prediction line.*

---

## 🛠️ Technologies Used

- **Python** - Programming language
- **Jupyter Notebook** - Interactive development environment
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical plots
- **Scikit-learn** - Machine learning model (Linear Regression)

---

## 💡 Key Insights

- Students with more study hours tend to perform better
- Previous scores are a strong predictor of future performance
- Adequate sleep positively impacts academic outcomes
- Practice papers significantly improve test scores

---

## 📁 Project Structure
```
student-performance-prediction/
├── data/
│   └── Student_Performance.csv    # Dataset
├── images/
│   └── output.png                 # Model results visualization
├── student.ipynb                  # Jupyter Notebook with analysis
└── README.md                      # Project documentation
```

---

## 🔍 Notebook Contents

The `student.ipynb` notebook includes:
1. **Data Loading & Exploration** - Understanding the dataset
2. **Data Preprocessing** - Cleaning and preparing data
3. **Exploratory Data Analysis (EDA)** - Visualizing patterns and relationships
4. **Model Training** - Building the Linear Regression model
5. **Model Evaluation** - Testing and measuring performance
6. **Results Visualization** - Plotting actual vs predicted values

