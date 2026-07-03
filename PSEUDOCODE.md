# GastroGuard – ALGORITHM

## Algorithm

START

1. Load the trained Logistic Regression model.
2. Load the Standard Scaler.
3. Load Label Encoders.
4. Display the Login Page.
5. Authenticate the user credentials.
6. If login is successful, open the Health Assessment page.
7. Collect all 36 patient health and lifestyle features.
8. Validate the entered input values.
9. Convert categorical features into numerical values using Label Encoders.
10. Scale the input features using the trained Standard Scaler.
11. Pass the processed data to the Logistic Regression model.
12. Predict the patient's Disease Class.
13. Calculate the prediction probability (Risk Percentage).
14. Classify the patient into:
    - Low Risk
    - Moderate Risk
    - High Risk
15. Display:
    - Risk Gauge
    - Risk Percentage
    - Risk Level
    - Personalized Health Recommendation
16. Save the patient details and prediction to Google Sheets.
17. Display the Patient Records Dashboard.
18. Allow searching, filtering, refreshing, and exporting records.

END
