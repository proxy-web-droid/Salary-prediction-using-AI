Employee Salary Prediction Project 🌟

This repository contains a machine learning project to predict employee salaries based on various features using regression models. The project includes data preprocessing, model training, performance visualization, and a Streamlit web application for interactive predictions, hosted via ngrok in Google Colab.

This is my link to Access my Streamlit App: https://a58a2df8e190.ngrok-free.app/

Overview 📊

Dataset: Uses Salary Data.csv, originally sourced from Kaggle, hosted at GitHub with features like Age, Gender, Education Level, Job Title, and YearsExperience to predict Salary.
Models: Implements Linear Regression, Random Forest, SVR, and Decision Tree Regressors, with the best model saved as best_model.pkl.
Visualizations: Includes a model comparison bar chart and plots for Salary Distribution, Salary by Education Level, Salary by Gender, Salary by Job Title (Top 20), and Years of Experience vs Salary.
Streamlit App: Provides a web interface for single and batch salary predictions, accessible via a public ngrok URL.

Prerequisites 🛠

Python 3.x 🐍
Google Colab 📈 (for running the notebook)
ngrok account 🌐 (for hosting the Streamlit app)
Required libraries: pandas, numpy, scikit-learn, matplotlib, streamlit, pyngrok, joblib

Setup Instructions 🚀

Clone the Repository:
git clone <your-repo-url>
cd <your-repo-folder>


Open in Google Colab:

Upload the provided Python script (salary_prediction_all_features_with_plots.py) to a new Colab notebook.
Copy and paste the script into a code cell.


Install Dependencies:

The script automatically installs required libraries when run in Colab.


Configure ngrok:

Sign up at ngrok.com and get your auth token.
Replace 'YOUR_NGROK_AUTH_TOKEN' in the script with your ngrok auth token.


Run the Script:

Execute the code cell in Colab. This will:
Load and preprocess the dataset.
Train models and save the best one.
Generate visualizations.
Create and host the Streamlit app, providing a public URL.





Usage 🎯

Visualizations

After running the script, the following plots will be displayed in Colab:

Model Comparison: Bar chart of R² Scores for each model.
Salary Distribution: Histogram with a density curve.
Salary by Education Level: Box plot.
Salary by Gender: Box plot.
Salary by Job Title (Top 20): Box plot.
Years of Experience vs Salary: Scatter plot.

Streamlit App

Access the app via the ngrok URL printed in the output (e.g., https://<random>.ngrok.io).
Features:
Single Prediction: Input Age, Gender, Education Level, Job Title, and YearsExperience to predict salary.
Batch Prediction: Upload a CSV with the same columns to predict salaries for multiple entries and download the results.



Files 📁

salary_prediction_all_features_with_plots.py: Main script with model training, visualizations, and Streamlit app setup.
app.py: Generated Streamlit application file.
best_model.pkl: Saved best-performing model.
README.md: This file.
LICENSE: Project license file.

Contributing 🤝

Feel free to fork this repository, submit issues, or create pull requests for enhancements like additional features or dataset updates.
License 📜

This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments 🙏

Dataset originally sourced from Kaggle, hosted on GitHub by the contributor.
Built with support from open-source libraries and tools.
Created on July 20, 2025, at 09:58 AM IST.
