# 🍷 Red Wine Dataset Analysis

This project explores the **Red Wine Quality** dataset through comprehensive visual and statistical analysis. The goal is to understand the relationships between different physicochemical properties and wine quality scores.

## 📊 Dataset

- **Source**: [UCI ML Repository – Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- **Type**: Red wine samples
- **Samples**: 1,599
- **Features**: 11 physicochemical attributes + 1 quality score (0–10)

## 🔍 Exploratory Data Analysis (EDA)

The notebook performs detailed EDA to extract insights and trends:

### ✅ Steps Covered

- Dataset loading and structure inspection
  - `.info()`, `.head()`, `.isnull()`, `.duplicated()`
- Cleaning
  - Duplicate row removal
- Correlation heatmap of features
- Histogram plots for each feature
- Pair plots to visualize feature interactions
- Bar plot of wine quality distribution
- Point plot: Alcohol vs. Quality
- Scatter plot: Alcohol vs. pH (colored by quality)

## 🛠 Tools Used

- `pandas` – data manipulation
- `seaborn`, `matplotlib` – data visualization
- `Jupyter Notebook` – interactive analysis

## 📁 Project Structure

```
📦 red-wine-analysis/
├── red_wine.ipynb         # Jupyter Notebook with full EDA
├── winequality-red.csv    # Dataset file (UCI Red Wine Quality)
└── README.md              # Project documentation
```

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/red-wine-analysis.git
cd red-wine-analysis
```

2. Launch the notebook:
```bash
jupyter notebook red_wine.ipynb
```

> Make sure `winequality-red.csv` is present in the same directory as the notebook.

## 📌 Future Work

- Add classification models (e.g., Logistic Regression, Random Forest)
- Hyperparameter tuning and cross-validation
- Performance metrics comparison and ROC analysis

## 📚 Reference

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.  
*Modeling wine preferences by data mining from physicochemical properties.*  
Decision Support Systems, Elsevier
