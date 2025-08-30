In this project, we aim to predict whether a telecom customer will leave the company (Churn) or stay.
The dataset contains various customer features, such as tenure, monthly charges, contract type, and subscribed services etc.
Our main goal is to use these features to determine if a customer will churn (Yes) or remain (No).
This model can help the company retain customers and reduce potential losses.

Features (X):
    customerID → Unique ID of the customer.
    gender → Customer's gender (Male/Female).
    SeniorCitizen → 1 if customer is senior, 0 otherwise.
    Partner → Whether the customer has a partner (Yes/No).
    Dependents → Whether the customer has dependents (Yes/No).
    tenure → Number of months the customer has stayed with the company.
    PhoneService → Whether the customer has phone service (Yes/No).
    MultipleLines → Whether the customer has multiple phone lines (Yes/No/No phone service).
    InternetService → Type of internet service (DSL, Fiber optic, No).
    OnlineSecurity → Whether online security is enabled (Yes/No/No internet).
    OnlineBackup → Whether online backup is enabled (Yes/No/No internet).
    DeviceProtection → Device protection service (Yes/No/No internet).
    TechSupport → Technical support service (Yes/No/No internet).
    StreamingTV → TV streaming service (Yes/No/No internet).
    StreamingMovies → Movie streaming service (Yes/No/No internet).
    Contract → Contract type (Month-to-month, One year, Two year).
    PaperlessBilling → Whether the customer uses paperless billing (Yes/No).
    PaymentMethod → Payment method (Electronic check, Mailed check, Bank transfer, Credit card).
    MonthlyCharges → The amount charged monthly.
    TotalCharges → Total amount charged.

Target (y):
    Churn → Whether the customer left the company (Yes) or stayed (No).