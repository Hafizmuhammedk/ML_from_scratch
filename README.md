# ML From Scratch

A practical machine learning repository built with Jupyter notebooks, focused on understanding concepts by implementing and experimenting step by step.

## Overview

This repository contains topic-wise notebooks covering:

- Data collection (CSV, JSON, APIs, web scraping)
- EDA (univariate and bivariate analysis, profiling)
- Missing-value handling and imputation
- Encoding and feature transformation
- Outlier detection and removal
- Scikit-learn pipelines and column transformers
- Regression models and metrics
- Logistic regression and gradient descent
- PCA and dimensionality reduction

## Repository Highlights

- 30+ focused learning modules in separate folders
- Mini datasets included for reproducible notebook runs
- From-scratch intuition notebooks for optimization topics
- Streamlit demo for logistic regression decision boundaries

## Tech Stack

- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib, Seaborn, Plotly
- Scikit-learn
- Streamlit

## Quick Start

### 1. Clone

```bash
git clone git@github.com:Hafizmuhammedk/ML_from_scratch.git
cd ML_from_scratch
```

### 2. Create virtual environment

```bash
python -m venv .venv
```

Activate it:

```bash
# Linux/macOS
source .venv/bin/activate

# Windows (PowerShell)
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run notebooks

```bash
jupyter notebook
```

## Run Interactive Demo

```bash
streamlit run logistic-regression-contd/streamlit-viz-tool.py
```

## Project Structure

```text
ML_from_scratch/
├── Fetching_Data_From_an-API/
├── Fetching_data_using_WebScraping/
├── Understanding_Data/
├── univariate-analysis/
├── bivariate-analysis/
├── handling-mixed-variables/
├── handling-missing-categorical-data/
├── imputing-numerical-data/
├── complete-case-analysis/
├── iterative-imputer/
├── knn-imputer/
├── missing-indicator/
├── ordinal-encoding/
├── one-hot-encoding/
├── normalization/
├── standardization/
├── power-transformer/
├── function-transformer/
├── binning-and-binarization/
├── handling-date-and-time/
├── feature-construction-and-feature-splitting/
├── outlier-removal-using-zscore/
├── outlier-removal-using-iqr-method/
├── outlier-detection-using-percentiles/
├── sklearn-pipelines/
├── column-transformer/
├── simple-linear-regression/
├── multiple-linear-regression/
├── polynomial-regression/
├── elasticnet-regression/
├── regression-metrics/
├── gradient-descent/
├── types-of-gradient-descent/
├── logistic-regression-contd/
├── pca/
└── toy-dataset-project/
```

## Notes

- This is a learning-first project; notebooks emphasize intuition and experimentation.
- Some folders include generated artifacts such as `.pkl`, `.html`, and `.gif` files.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

## License

If you want to make reuse explicit, add a `LICENSE` file (for example MIT).
