Machine Learning Tasks
Overview
This repository contains two machine learning projects demonstrating the complete workflow of data preprocessing, model training, and performance evaluation. The tasks included are:
Email Spam Classification – classifying emails as spam or not spam using text data.
MNIST Digit Recognition – recognizing and classifying handwritten digits from 0 to 9 using image data.
Both projects showcase practical applications of machine learning for text classification and image recognition.

Task 1: Email Spam Classification

Objective:
Build a machine learning model to classify emails as spam or not spam using a labeled dataset.

Workflow:

Data Preprocessing

Cleaned and normalized raw email text.

Removed unnecessary characters, punctuation, and stopwords.

Feature Extraction

Converted text into numerical features using vectorization techniques.

Model Training

Trained a supervised learning model (e.g., Naive Bayes or Logistic Regression) on the processed dataset.

Evaluation

Evaluated the model using accuracy, precision, recall, and confusion matrix.

Achieved strong performance in detecting spam emails.

Files included:

spam_classification.ipynb – complete code for preprocessing, training, and evaluation.

Task 2: MNIST Digit Recognition

Objective:
Build a machine learning model to recognize and classify handwritten digits (0–9) from the MNIST dataset.

Workflow:

Data Loading & Preprocessing

Loaded MNIST images in IDX format.

Normalized pixel values and reshaped images into feature vectors for the model.

Model Training

Trained a Logistic Regression model to classify digits.

Evaluation

Measured performance using accuracy, classification report, and confusion matrix.

Visualized sample predictions to validate the model.

Files included:

mnist_digit_recognition.ipynb – complete code for preprocessing, training, evaluation, and visualization.
machine-learning-tasks/
│
├── spam_classification.ipynb
├── mnist_digit_recognition.ipynb
├── README.md
└── .gitignore
├── mnist_digit_recognition.ipynb
├── README.md
└── .gitignore
