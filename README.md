# CS4372_HW2_Shyam_Rudy
Dataset Link: ([url](https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval?resource=download&select=Loan.csv))

Overview:
This project predicts whether a loan application will be approved or not using financial, demographic, and credit-history attributes from the Financial Risk for Loan Approval dataset.
We employ four classifiers: Decision Tree, Random Forest, AdaBoost, and XGBoost.
Each model is tuned, tested, and compared using Accuracy, Precision, Recall, F1 Score, and ROC AUC metrics.

How to Run:
Open the .ipynb notebook in Jupyter Notebook, VS Code, or Google Colab.

Run all cells in order:
1. Load Loan.csv and check dataset info
2. Perform preprocessing (encode categorical, scale numeric, handle class imbalance)
3. Split into training and test sets
4. Train & tune the four models using GridSearchCV
5. Evaluate performance metrics
6. Visualize output (decision tree, ROC curves, feature importance)

Files Included:

CS4372HW2_Shyam_Rudy.ipynb — complete code

Loan.csv — dataset

HW2_Report_Shyam_Rudy.pdf — report

