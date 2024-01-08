ONSITE-HEALTH-DIAGNOSTIC-WEBAPP:

Onsite Health Diagnostic Web App
Introduction
This web application is designed for the prediction of multiple health conditions, including Diabetes, Heart Disease, and Parkinson's Disease, using Machine Learning models. The app provides an interactive interface for users to input relevant medical information and receive predictions for each respective health condition.

Features
Diabetes Prediction:

Input parameters such as Number of Pregnancies, Glucose Level, Blood Pressure, etc.
Click on the "Diabetes Test Result" button to obtain the prediction.
Heart Disease Prediction:

Input parameters including Age, Sex, Chest Pain types, etc.
Click on the "Heart Disease Test Result" button to get the prediction.
Parkinson's Disease Prediction:

Input various parameters related to voice characteristics.
Click on the "Parkinson's Test Result" button for the prediction.
Technologies Used
Python
Streamlit
Pickle (for model serialization)
Machine Learning models for Diabetes, Heart Disease, and Parkinson's Disease prediction
Setup
Clone the repository:

bash
Copy code
git clone <repository-url>
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the web application:

bash
Copy code
streamlit run app.py
Open the provided URL in your web browser.

Usage
Select the desired health condition from the sidebar navigation.
Enter the relevant medical information in the input fields.
Click on the corresponding "Test Result" button to obtain the prediction.
View the prediction result displayed on the screen.
Contribution
Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

License
This project is licensed under the MIT License.
