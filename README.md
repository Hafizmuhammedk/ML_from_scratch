# ML From Scratch

A hands-on machine learning repository focused on core concepts, preprocessing, feature engineering, and regression/classification workflows using Python notebooks.

## What this repo contains

This project is organized as topic-wise folders, mostly with Jupyter notebooks and small datasets to practice each concept end-to-end.

Main areas covered:

- Data collection (`working_with_csv_files`, `working_with_json`, `Fetching_Data_From_an-API`, `Fetching_data_using_WebScraping`)
- Exploratory analysis (`univariate-analysis`, `bivariate-analysis`, `Understanding_Data`, `pandas-profiling`)
- Data preprocessing (missing values, encoding, scaling, transformations)
- Feature engineering (`feature-construction-and-feature-splitting`, date-time handling, binning)
- Outlier handling (`outlier-removal-*`, `outlier-detection-*`)
- Model pipelines (`sklearn-pipelines`, `column-transformer`)
- Regression topics (simple, multiple, polynomial, elastic net, metrics)
- Logistic regression and optimization (`gradient-descent`, `types-of-gradient-descent`, `logistic-regression-contd`)
- Dimensionality reduction (`pca`)

## Tech stack

- Python
- Jupyter Notebook
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
- Streamlit (for one interactive demo)

## Getting started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/ML_from_scratch.git
cd ML_from_scratch
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
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

Open any folder and run the corresponding `.ipynb` file.

## Run the Streamlit demo

This repo includes an interactive logistic regression visual tool:

```bash
streamlit run logistic-regression-contd/streamlit-viz-tool.py
```

## Repository structure (high level)

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

- Most notebooks are educational experiments and demonstrations.
- Some folders include trained artifacts (`.pkl`) and generated files (`.html`, `.gif`).
- Datasets are small and primarily for learning/practice purposes.

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a pull request

## License

Add a license file (`LICENSE`) if you want others to reuse this project with clear terms.
