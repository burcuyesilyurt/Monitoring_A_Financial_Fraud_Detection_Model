# Monitoring_A_Financial_Fraud_Detection_Model

A summary and preview are provided below.

reference.csv and analysis.csv
Column	Description
* 'timestamp'	Date of the transaction.
* 'time_since_login_min'	Time since the user logged in to the app.
* 'transaction_amount'	The amount of Pounds(£) that users sent to another account.
* 'transaction_type'	Transaction type:
* CASH-OUT - Withdrawing money from an account.
* PAYMENT - Transaction where a payment is made to a third party.
* CASH-IN - This is the opposite of a cash-out. It involves depositing money into an account.
* TRANSFER - Transaction which involves moving funds from one account to another.
* 'is_first_transaction'	A binary indicator denoting if the transaction is the user's first (1 for the first transaction, 0 otherwise).
* 'user_tenure_months'	The duration in months since the user's account was created or since they became a member.
* 'is_fraud'	A binary label indicating whether the transaction is fraudulent (1 for fraud, 0 otherwise).
* 'predicted_fraud_proba'	The probability assigned by a detection model indicates the likelihood of a fraudulent transaction.
* 'predicted_fraud'	The predicted classification label is calculated based on predicted fraud probability by the detection model (1 for predicted fraud, 0 otherwise).
