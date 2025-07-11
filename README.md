### SMS Spam Detection using Machine Learning

This project focuses on building a machine learning model to detect spam messages from SMS text data. It uses text preprocessing and classification techniques to differentiate between spam and ham (non-spam) messages.

## Project Objectives
- Load and clean SMS text data

- Visualize the class distribution of spam vs. ham

- Extract text features using TF-IDF

- Train a Multinomial Naive Bayes model

- Evaluate the model using standard metrics

##  ML Techniques Used
- Text Vectorization: TfidfVectorizer

- Classification Model: Multinomial Naive Bayes

- Evaluation: Accuracy, Confusion Matrix, Classification Report

## Dataset Info
Source: spam.csv

- Contains SMS messages labeled as ham (legit) or spam.

- Unused columns were dropped, and labels were encoded (ham=0, spam=1).

## Exploratory Analysis
  - Visualized label distribution

  - Calculated average number of words per message

  - Counted total unique words in the dataset

## How to Run
1. Clone the repo or download the notebook.

2. Install dependencies:

```bash

pip install pandas numpy seaborn matplotlib scikit-learn
Run the Jupyter Notebook (.ipynb file).
```

3. Ensure the dataset path is correct in your local setup.

## Results

The trained model is evaluated using:

- Accuracy Score

- Confusion Matrix

- Classification Report

##  Folder Structure
  ```
sms-spam-detection/
├── spam.csv
├── spam_detection_model.ipynb
└── README.md

```
##  Future Improvements
- Use more advanced models like SVM or BERT

- Add web app using Streamlit or Flask

Include message pre-cleaning (stopwords, stemming, etc.)
