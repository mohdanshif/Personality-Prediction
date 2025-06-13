# 🧠 Personality Prediction Web App

This project involves analyzing a personality dataset using Exploratory Data Analysis (EDA) and building a personality type prediction model, which is then deployed using a Flask web application.

# 📂 Project Structure
```bash
├── personality_dataset.ipynb   # Jupyter notebook with EDA and model building
├── app.py                      # Flask application
├── templates/
│   └── form.html              # Frontend for the web app
├── knn_model.pkl                   # Saved ML model
└── README.md                   # Project documentation
```
# 📊 1. Exploratory Data Analysis (EDA)

Dataset Overview: Understanding feature types, missing values, and data distributions.

Visualizations:

Feature correlations

Distribution plots (e.g., social activity, energy levels)

Personality trait trends

Preprocessing:

Handling missing data

Label encoding

Feature scaling

# 🤖 2. Model Building

Machine learning model trained using:

Logistic Regression / KNN / Random Forest (as applicable)

Target: Predict personality type (e.g., Introvert, Extrovert)

Evaluation: Accuracy, Confusion Matrix, etc.

Saved using joblib/pickle as model.pkl

# 🌐 3. Flask Web App 

Built using Flask

Takes user input (e.g., behavioral traits)

Displays predicted personality type

# 🚀 How to Run the Project

1. Clone the Repository
```bash
git clone https://github.com/yourusername/personality-prediction-app.git
cd personality-prediction-app
```
2. Install Dependencies
```bash
pip install -r requirements.txt
```
3. Run Flask App
```bash
python app.py
```
4. Open in Browser

Visit http://127.0.0.1:5000 in your browser.
