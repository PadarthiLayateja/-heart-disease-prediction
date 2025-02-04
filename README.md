# heart-disease-prediction
Heart Disease Prediction Model
Overview
This project aims to predict the presence of heart disease based on certain medical attributes. The model uses logistic regression and is trained on a dataset containing patient information.
Dataset
The dataset used in this project is a CSV file named heart (1).csv, which contains the following columns:
age: Age of the patient
cp: Chest pain type (0-3)
thalach: Maximum heart rate achieved
target: Presence of heart disease (1) or absence (0)
Dependencies
To run this project, you need the following Python libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
You can install these dependencies using pip:
bash
Copy
pip install pandas numpy matplotlib seaborn scikit-learn joblib
Model Training and Evaluation
The model is trained using logistic regression. The dataset is split into training and testing sets with an 80/20 ratio. The model's performance is evaluated using accuracy, confusion matrix, classification report, and ROC AUC score.
Usage
Training the Model
Ensure you have the dataset file heart (1).csv in the same directory as the script.
Run the script to train the model and evaluate its performance.
Making Predictions
The script includes a function predict_heart_disease() that allows users to input their medical attributes and receive a prediction. To use this function:
Run the script.
Follow the prompts to enter your age, chest pain type, and maximum heart rate achieved.
The script will output whether heart disease is present or not.
Saving the Model
The trained model is saved as heart_disease_model.pkl using joblib. This allows you to load the model later for predictions without retraining.
