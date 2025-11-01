# 🎓 Student Performance Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

Predicting students' academic performance using Linear Regression.

---

## 📝 Description

This project analyzes student data to predict final grades using **Linear Regression**. The model examines various academic and behavioral factors to forecast student performance and identify patterns that influence academic success.

---

## 📊 Dataset

The dataset (`Student_Performance.csv`) contains **10,007 records** with the following features:

| Feature | Description |
|---------|-------------|
| **Hours Studied** | Time spent studying |
| **Previous Scores** | Past exam results |
| **Extracurricular Activities** | Participation in non-academic activities (0 or 1) |
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

---

## 📈 Results

### Model Performance

| Metric | Value |
|--------|-------|
| **Mean Squared Error (MSE)** | 4.24 |
| **Root Mean Squared Error (RMSE)** | 2.06 |
| **R-squared (R²)** | 0.9884 |

> **Note:** The model achieves **98.84% accuracy** (R²), indicating excellent predictive performance with minimal error.

### Visualizations

**Correlation Matrix:**
![Correlation Matrix](images/correlation_heatmap.png)

**Model Performance:**
![Predicted vs Actual Scores](/Users/aljawharah/Desktop/Tuwaiqbootcame/linear-regression-task-Aljwharah1/output.png)

*The scatter plot shows strong correlation between predicted and actual scores, with most points closely aligned to the ideal prediction line (red dashed line).*

---

## 🛠️ Technologies Used

- **Python 3.10** - Programming language
- **Jupyter Notebook** - Interactive development environment
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical plots and heatmaps
- **Scikit-learn** - Machine learning (Linear Regression model)

---

## 💡 Key Findings

- The Linear Regression model demonstrates **high accuracy** with R² = 0.9884
- **Low RMSE (2.06)** indicates predictions are very close to actual values
- Correlation analysis reveals relationships between student behavior and performance
- All features contribute meaningfully to predicting student outcomes

---

## 📁 Project Structure
```
student-performance-prediction/
├── data/
│   └── Student_Performance.csv    # Dataset (10,007 records)
├── images/
│   ├── correlation_heatmap.png    # Correlation matrix visualization
│   └── output.png                 # Model results visualization
├── student.ipynb                  # Jupyter Notebook with full analysis
└── README.md                      # Project documentation
```
