# CS103-data-analysis
The repository contains the two assignments of the course: Data analysis using Scikit-learn Logistic Regression and Linear Regression models
## Prompt
1. First assignment: Predict the loan amount for which a customer can request a bank with his/her collateral house.
     - Dataset: [house_loan.csv](house_loan_updated.csv)
          - Gender: Gender of customer requesting for a loan (‘F’ or ‘M’).
          - Age: Age of customer requesting for a loan (non-negative values).
          - Income (USD): Income of customer requesting for a loan (non-negative values).
          - Income Stability: Income stability of customer requesting for a loan (“Low” or “High”).
          - Property Age: Age of the property (non-negative number of days).
          - Property Location: Location of the property (“Rural”, “Urban”, and “Semi-Urban”).
          - Property Price: Price of the property (USD).
          - Loan Sanction Amount (USD): Ammount of loan the customer can requst for (USD, target value)
     - Model: Scikit-learn Linear regression
2. Second assignment: Predict whether a particular person has a heart disease or not based on 14 attributes.
     - Dataset: [heart-disease.csv](heart-disease.csv)
          - age: The person’s age in years
          - sex: The person’s sex (1 = male, 0 = female)
          - cp: chest pain type
               - Value 0: asymptomatic
               - Value 1: atypical angina
               - Value 2: non-anginal pain
               - Value 3: typical angina
          - trestbps: The person’s resting blood pressure (mm Hg on admission to the hospital)
          - chol: The person’s cholesterol measurement in mg/dl (mg/dl: milligrams per decilitre)
          - fbs: The person’s fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false) (Fasting blood glucose: A test to determine how much glucose (sugar) is in a blood sample after an overnight without eating).
          - restecg: resting electrocardiographic results
               -  Value 0: showing probable or definite left ventricular hypertrophy by Estes’ criteria
               - Value 1: normal
               - Value 2: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
          - thalach: The person’s maximum heart rate achieved
          - exang: Exercise induced angina (1 = yes; 0 = no)
          - oldpeak: ST depression induced by exercise relative to rest (‘ST’ relates to positions on the
     ECG plot)
          - slope: the slope of the peak exercise ST segment
               - 0: downsloping
               - 1: flat
               - 2: upsloping
          - ca: The number of major vessels (values in 0–3)
          - thal: A blood disorder called thalassemia
               - Value 0: NULL (dropped from the dataset previously
               - Value 1: fixed defect (no blood flow in some part of the heart)
               - Value 2: normal blood flow
               - Value 3: reversible defect (a blood flow is observed but it is not normal)
     - Model: Scikit-lear Logistic regression
