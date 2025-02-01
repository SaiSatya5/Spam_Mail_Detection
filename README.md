# Spam_Mail_Detection
This project implements a Spam Mail Detection System using Logistic Regression. The system is designed to classify email messages as either Spam or Ham (non-spam). By training a logistic regression model on labeled email data, it can predict the likelihood of an email being spam based on various features extracted from the text of the email.

Features :
- Spam detection: Classifies email messages as either spam or not.
- Logistic Regression: Utilizes a logistic regression model to make predictions.
- Data preprocessing: Includes text vectorization and normalization of features.
- Model evaluation: Evaluates the model's performance using the accuracy

Requirements :
- Python 3.6+
Libraries:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

You can install these dependencies using pip:

pip install numpy pandas scikit-learn matplotlib seaborn

Dataset
This project uses the SMS Spam Collection Dataset, which contains a set of SMS messages categorized as spam or ham. The dataset consists of labeled examples of spam and ham messages in a .csv format.

Dataset Columns:
- label: The label for the message, either "spam" or "ham".
- message: The text content of the SMS message.
