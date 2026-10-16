# Diabetes risk classification on CDC-NHANES

Individual assignment for the Data Mining course at JADS (2024).

Classifies participants of the NHANES 2013–2014 survey as Normal, Prediabetes or Diabetes.

- Notebook: [`diabetes_risk_nhanes.ipynb`](diabetes_risk_nhanes.ipynb)
- Report: [`report.pdf`](report.pdf)

The notebook covers data merging and cleaning (MICE imputation), exploratory analysis, K-Means and agglomerative clustering, association rule mining, and four classifiers (logistic regression, SVM, random forest, neural network) tuned with Bayesian optimisation, each with and without SMOTE.

Best test accuracy: random forest (86.8%). Prediabetes was hard to detect for all models; SMOTE improved it slightly at the cost of overall accuracy. Details are in the report.

## Running it
Put the NHANES CSV files in `data/` (see [`data/README.md`](data/README.md)), install `requirements.txt`, and open the notebook.
