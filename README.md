**Salary Prediction App Readme**

This Salary Prediction App is a Python application that predicts the salary of computer programmers based on various input parameters such as experience years, education level, age, language proficiency, team size, and project completion rate. The application utilizes a Random Forest Regressor model trained on synthetic data generated for computer programmers' work in the Philippines.

### Requirements
To run the Salary Prediction App, you need to have the following installed:
- Python (version 3.x)
- Required Python libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `tkinter`

### Usage
1. Clone or download the repository to your local machine.
2. Navigate to the directory containing the source code.
3. Run the following command to launch the Salary Prediction App:

   ```
   python salary_prediction_app.py
   ```

4. Once the app window opens, enter the input values for experience years, education level, age, language proficiency, team size, and project completion rate. Select the gender from the dropdown menu.
5. Click the "Predict Salary" button to obtain the predicted salary based on the input parameters.
6. A message box will display the predicted salary.

### Files
- `salary_prediction_app.py`: Contains the main Python code for the Salary Prediction App.
- `README.md` (this file): Provides instructions on how to use the Salary Prediction App.

### Note
- The synthetic data used for training the model is generated within the script. However, you can replace it with your own dataset if desired.
- The model used for prediction is a Random Forest Regressor with 100 estimators. You can explore other models and parameters for potentially better performance.
- The application is built using Tkinter, the standard GUI toolkit for Python.

### Author
This Salary Prediction App was created by [Bryan N. Lomerio].
