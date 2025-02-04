# ❤️ Heart Disease Prediction Web App

## Overview 🧐

This project is a **Heart Disease Prediction System** that leverages machine learning (ML) to predict whether an individual has heart disease based on their medical data. The app uses a **Logistic Regression** model trained on a dataset of heart disease-related features like age, chest pain type, and maximum heart rate. The backend is built using **Flask** (Python), and the frontend is built using **HTML, CSS, and JavaScript**.

### Key Features ✨:
- 🔍 Predict heart disease based on user input.
- 🖥️ Simple, intuitive web interface.
- ⚡ Flask API to handle predictions.
- 📦 Model is stored and loaded via `joblib`.

## How It Works 🔄

1. The user inputs three features:
   - **Age**: The age of the individual.
   - **Chest Pain Type** (`cp`): Type of chest pain (0-3).
   - **Maximum Heart Rate** (`thalach`): The maximum heart rate achieved.

2. The input data is sent to the backend, where a pre-trained **Logistic Regression** model makes a prediction: either **"Heart Disease Present"** or **"No Heart Disease"**.

3. The result is displayed on the frontend in real-time.

## Technologies Used 🛠️

- **Backend**:
  - Python 🐍
  - Flask 🥖
  - Joblib (for saving and loading the model) 💼
  - pandas (for data manipulation) 📊
  
- **Frontend**:
  - HTML 📄
  - CSS 🎨
  - JavaScript 💻 (for API calls)
  - AJAX 🌐 (for sending requests and handling responses)

- **Machine Learning**:
  - Logistic Regression 🔍
  - Scikit-learn 🤖
  
## How to Run the Project Locally 🏡

Follow these steps to run the project on your local machine:

### Prerequisites ⚡:

1. **Python 3.x** installed on your machine.
2. **Visual Studio Code (VS Code)** or another code editor of your choice.
3. **Python libraries**: `Flask`, `joblib`, `pandas`, `scikit-learn` installed.

### Steps to Set Up 📝:

1. **Clone this repository**:

   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
