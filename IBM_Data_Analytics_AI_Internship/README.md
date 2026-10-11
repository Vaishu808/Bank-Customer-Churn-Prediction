
# Bank Customer Churn Prediction & Retention Analytics

End-to-end data cleaning, EDA, five-model validation comparison and leakage-safe Gradient Boosting decision-threshold tuning.

## Dataset
`[Churn_Modelling.csv](https://www.kaggle.com/datasets/louishgy/churn-modelling)`
## Run in VS Code
1. Open this folder in VS Code.
2. Create a Python environment: `python -m venv .venv`
3. Activate it (Windows): `.venv\Scripts\activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Open `Vaishnavi_BankCustomerChurn.ipynb`, select the environment as kernel, then **Run All**.

Outputs are written to `outputs/`. The test set is never used for threshold selection.

## Methodology
60/20/20 stratified train/validation/test split; preprocessing is fit only on training data. Gradient Boosting is the pre-specified retention-focused model. A threshold is selected using validation F1 subject to illustrative accuracy and recall criteria; the untouched test set is evaluated only after selection.

## Limitations
Risk thresholds are illustrative, not deployed banking policy. Findings are associative. Verify data source and internship policy regarding reuse of earlier work.
