🩺 Diabetes Prediction Web Application

A machine learning–powered web application that predicts whether a person is diabetic based on medical attributes.
The app uses a trained ML model and provides an easy-to-use interface built with Streamlit.

📌 Project Overview

Early detection of diabetes is crucial for timely treatment and prevention of complications.
This project leverages machine learning to analyze patient health metrics and predict the likelihood of diabetes.

The application allows users to input medical data and instantly receive a prediction.

🚀 Features

🧠 Machine Learning–based prediction

🌐 Interactive web interface using Streamlit

⚡ Real-time results

🧪 Input validation and error handling

📦 Lightweight and easy to deploy

🛠️ Tech Stack

Programming Language: Python

Machine Learning: Scikit-learn

Web Framework: Streamlit

Data Processing: NumPy

Model Storage: Pickle


📊 Input Parameters

The model predicts diabetes based on the following features:

Feature	Description
Pregnancies	Number of pregnancies
Glucose	Plasma glucose concentration
BloodPressure	Diastolic blood pressure (mm Hg)
SkinThickness	Triceps skin fold thickness (mm)
Insulin	2-Hour serum insulin
BMI	Body Mass Index
DiabetesPedigreeFunction	Genetic influence
Age	Age of the person
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone <your-repo-url>
cd deployment streamlit

2️⃣ Create a virtual environment (recommended)
python -m venv venv


Activate it:

Windows

venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

▶️ Running the Application
🔹 Run the Streamlit web app
streamlit run web_app.py


The app will open automatically in your browser at:

http://localhost:8501

🔹 (Optional) Test the model directly
python pred_diabetes.py

🧪 Model Output

0 → Person is Not Diabetic

1 → Person Is Diabetic

📈 Dataset Used

PIMA Indians Diabetes Dataset

Widely used benchmark dataset for binary classification in healthcare ML projects

🧠 Future Improvements

Add probability/confidence score

Improve UI with sliders and number inputs

Deploy on Streamlit Cloud

Add model explainability (SHAP / feature importance)

Improve accuracy with hyperparameter tuning

👤 Author

Hitesh Kumar
Computer Science Undergraduate
AI / ML Enthusiast
