# Loan-Default-Detector
Bank Credit Card Application Fraud Detector
This project builds a Loan Default Detector to predict credit card applicants at risk of default. <br>
The two Jupyter Notebooks contain all the EDA and modeling.<br>
To run MLflow-enabled HistGradientBoosting model hyperparameter tuning:
<pre>mlflow run . --experiment-name loan -P n_trials=64 -P class_balance=True -P objective_metric=ap -P undersample=False</pre>

