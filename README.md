💼 Salary Prediction Web App

This is a Machine Learning-powered Streamlit web application that predicts employee salary based on:

⦁	📈 Annual performance rating

⦁	🧠 Total work experience (in years)



📌 Features:

⦁	Predict salary using

⦁	Linear Regression

⦁	Random Forest

⦁	K-Nearest Neighbors (KNN)

🧪 How to Run (on Google Colab):

1. Clone this repo or upload app.py, model files and dataset:

   ⦁	salary_model.pkl, rf_model.pkl, knn_model.pkl

   ⦁	salarydata.csv

2. Install required packages:

   ⦁	5!pip install streamlit pyngrok scikit-learn pandas matplotlib seaborn joblib


3. Set up your ngrok authtoken:

    !ngrok config add-authtoken YOUR_NGROK_AUTHTOKEN

4. Run the app:

   !streamlit run app.py &>/content/logs.txt &
  
   from pyngrok import ngrok
  
   public_url = ngrok.connect("http://localhost:8501")
  
   print(public_url)

5 Open the provided public link.
