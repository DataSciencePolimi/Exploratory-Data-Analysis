# Notebook EDA 📊

A hands-on collection of Jupyter notebooks for learning and practicing **Exploratory Data Analysis (EDA)**.

This repository is organized as a step-by-step workflow:
1. Understand your dataset
2. Exploratory Data Analysis (EDA)
2.1 Explore univariate patterns
2.2 Explore multivariate patterns
3. Analyze bivariate and multivariate relationships
4. Detect outliers
5. Handle missing values
6. Train baseline ML models
6.1 Classification
6.2 Regression
6.3 Clustering

It includes multiple CSV datasets (stored in `datasets/`) so each notebook can be executed directly.

## Repository Structure 🗂️

### Notebooks 📓
- `1. Dataset Overview.ipynb`  
  Initial data inspection: shape, data types, summary statistics, and first quality checks.

- `2.1 EDA - Univariate.ipynb`  
  Distribution analysis for single variables (numerical and categorical).

- `2.2 EDA - Bivariate and Multivariate.ipynb`  
  Relationship analysis using pairwise comparisons, grouped summaries, and multivariate visualizations.

- `3. Outliers.ipynb`  
  Outlier detection methods and interpretation.

- `4. Missing Values.ipynb`  
  Missing data inspection and practical handling/imputation techniques.

- `5.1 Model - Classification.ipynb`  
  End-to-end supervised learning workflow for classification tasks: preprocessing, model training, and evaluation.

- `5.2 Model - Regression.ipynb`  
  End-to-end supervised learning workflow for regression tasks with appropriate metrics and model diagnostics.

- `5.3 Model - Clustering.ipynb`  
  Unsupervised learning workflow for clustering, including cluster quality analysis and interpretation.

### Datasets 🧪
- `datasets/california-housing.csv`
- `datasets/flights_seaborn.csv`
- `datasets/healthcare-dataset-stroke-data.csv`
- `datasets/iris_seaborn.csv`
- `datasets/outlier_detection_dataset.csv`
- `datasets/synthetic_stroke_data.csv`
- `datasets/tips_seaborn.csv`
- `datasets/titanic_seaborn.csv`

## Getting Started 🚀

### 1. Clone the repository 📥
```bash
git clone https://github.com/DataSciencePolimi/Exploratory-Data-Analysis
cd Exploratory-Data-Analysis
```

### 2. Create and activate a virtual environment (recommended) 🧰
```bash
python -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies 📦
```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn scipy
```

## Suggested Learning Path 🧭

For a structured learning flow, run notebooks in this order:
1. `1. Dataset Overview.ipynb`
2. `2.1 EDA - Univariate.ipynb`
3. `2.2 EDA - Bivariate and Multivariate.ipynb`
4. `3. Outliers.ipynb`
5. `4. Missing Values.ipynb`
6. `5.1 Model - Classification.ipynb`
7. `5.2 Model - Regression.ipynb`
8. `5.3 Model - Clustering.ipynb`

## Goals of This Repository 🎯

- Build intuition for reading and profiling real datasets
- Practice selecting the right visual/statistical technique for each question
- Learn robust preprocessing patterns before modeling
- Improve reproducibility in data analysis workflows

## Notes 📝

- Dataset files are stored in `datasets/`; if you move them again, update notebook file paths accordingly.
- If plots do not display, verify your Jupyter kernel and package installation.
- Some notebooks may require rerunning cells from top to bottom after kernel restarts.

## Author 👤

[Riccardo Campi](https://scholar.google.com/citations?user=JWSoz7EAAAAJ&hl=it)

## License ⚖️

This project is licensed under the MIT License. See [LICENSE.txt](LICENSE.txt) for details.
