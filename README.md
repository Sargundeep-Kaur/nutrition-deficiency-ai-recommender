

# Nutrition Deficiency & Personalized Diet Recommendation System

An AI/ML-based web application built with Flask that identifies potential nutrition deficiency risks and recommends personalized diet plans based on user inputs.

## Features

- **No Manual Dataset Required:** A synthetic dataset is generated automatically when the dataset is missing.
- **Automatic Model Training:** The machine learning model is trained and saved automatically if the saved model is unavailable.
- **Nutrition Deficiency Detection:** A rule-based engine checks for potential nutrition-related concerns.
- **Personalized Diet Recommendations:** Recommends a suitable diet-plan category based on user information.
- **Interactive Web Interface:** Users can enter their details and view predictions and dietary suggestions through a Flask web application.

## Tech Stack

- **Language:** Python
- **Web Framework:** Flask
- **Machine Learning:** Scikit-learn, Random Forest
- **Data Processing:** Pandas, NumPy
- **Model Persistence:** Joblib
- **Frontend:** HTML, CSS

## Project Structure

```text
nutrition-deficiency-ai-recommender/
├── app.py
├── requirements.txt
├── README.md
├── src/
│   ├── train_model.py
│   ├── recommend.py
│   └── rule_engine.py
├── templates/
│   └── index.html
├── data/
└── model/
```

## Installation and Setup

### Prerequisites

- Python 3
- pip

### 1. Clone the repository

```bash
git clone https://github.com/Sargundeep-Kaur/nutrition-deficiency-ai-recommender.git
cd nutrition-deficiency-ai-recommender
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python app.py
```

### 4. Open the application

Open the following URL in your browser:

http://127.0.0.1:5000

The application can generate synthetic training data and train the model automatically when required, depending on the implementation.

## How It Works

1. The user enters nutrition-related information through the web form.
2. The Flask application processes the submitted information.
3. The machine learning model predicts a diet-plan category.
4. The rule-based engine checks for potential nutrition-related concerns.
5. The application displays the prediction and relevant dietary suggestions.

## Future Improvements

- Evaluate model performance using precision, recall, F1-score, and a confusion matrix.
- Train and test the model on reliable, appropriately sourced nutrition datasets.
- Improve the user interface and input validation.
- Deploy the application online.
- Enhance recommendations using validated nutrition guidelines.

## Disclaimer

This project is intended for educational and demonstration purposes only. Synthetic data and rule-based checks may not reflect real-world nutritional conditions. Predictions are not medical diagnoses and should not replace advice from a qualified healthcare professional.

## Author

**Sargundeep Kaur**

- GitHub: https://github.com/Sargundeep-Kaur
