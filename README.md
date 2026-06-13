# FUTURE_DS_03 - Email Spam Detection System

## Project Overview

This project uses Machine Learning to classify messages as Spam or Ham (Not Spam). The model is trained using the SMS Spam Collection Dataset and uses TF-IDF Vectorization with a Naive Bayes Classifier for prediction.

## Objective

Build an email/message spam detection system and visualize the results through a simple dashboard.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Flask
- HTML

## Dataset

SMS Spam Collection Dataset

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Data Exploration
4. Spam vs Ham Visualization
5. Text Vectorization using TF-IDF
6. Train-Test Split
7. Model Training using Naive Bayes
8. Model Evaluation
9. Confusion Matrix Analysis
10. Custom Email Prediction
11. Dashboard Creation

## Visualizations

### Spam vs Ham Distribution
Shows the number of spam and ham messages in the dataset.

### Confusion Matrix
Displays the performance of the classification model.

## Model Performance

- Algorithm: Multinomial Naive Bayes
- Vectorization: TF-IDF
- Accuracy: (Add your obtained accuracy here)

## Dashboard Features

- Spam vs Ham Chart
- Confusion Matrix
- Model Accuracy Display
- Simple Web Dashboard using Flask

## Screenshots

### Spam vs Ham Chart
(screenshots/spam_ham_count.png)

### Confusion Matrix

(screenshots/confusion_matrix.png)
### Dashboard

(screenshots/dashboard.png)

## How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn flask
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

## Project Structure


FUTURE_DS_03/
│
├── data/
│   └── spam.csv
│
├── screenshots/
│   ├── spam_ham_count.png
│   ├── confusion_matrix.png
│   └── dashboard.png
│
├── spam_detection.ipynb
├── dashboard.html
├── app.py
└── README.md
```

## Author

Nishanth Y Poojary

## Internship

Future Interns – Data Science & Analytics Track