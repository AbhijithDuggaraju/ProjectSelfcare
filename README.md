# ProjectSelfcare
This project is a machine learning-based system that provides personalized skin care and hair care recommendations based on user inputs such as age, stress level, sleep patterns, severity, and specific concerns.

Overview

The system uses a hybrid approach combining ensemble learning and collaborative filtering to generate accurate and explainable recommendations. It also provides confidence scores and key contributing factors for each prediction.

Features

Personalized skin and hair care recommendations

Stacked ensemble model (Random Forest, Gradient Boosting, Logistic Regression)

Collaborative filtering using nearest neighbors

Confidence-based predictions with probability scores

Feature engineering with interaction and risk features

Model calibration for improved probability estimation

Synthetic dataset generation for training

Explainability through top contributing features

Model Architecture

Base Models:

Random Forest Classifier

Gradient Boosting Classifier

Shallow Random Forest

Meta Model:

Logistic Regression

Additional Components:

Isotonic calibration

Collaborative filtering (KNN-based)

Feature scaling and encoding

Project Structure
ProjectSelfcare/
│── ProjectSelfCare.ipynb
│── selfcare_model_v3.pkl
│── README.md
Installation

Install required dependencies:

pip install numpy pandas scikit-learn joblib
Usage
Run in Google Colab

Open the notebook and execute all cells.

Run Locally
python your_script.py
Input Parameters
Skin Care

Age

Gender

Skin type

Concern type

Severity

Sleep duration

Hair Care

Age

Gender

Stress level

Hair concern

Hair damage level

Output

Recommended treatment type (home, mixed, medical)

Confidence score

Probability distribution across classes

Key influencing factors

Step-by-step recommendations

Disclaimer

This system is trained on synthetic data and is intended for educational purposes only. It is not a substitute for professional medical advice. Users should consult a qualified professional before making health-related decisions.

Future Improvements

Web-based interface (Flask or React)

Integration with real-world datasets

Deployment as an API

User feedback and personalization loop

Author

Abhijith Duggaraju
B.Tech Information Technology
Interest areas: Machine Learning, Deep Learning, Web Development
