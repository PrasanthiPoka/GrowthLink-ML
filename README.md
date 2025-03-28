# GrowthLink-ML
GrowthLink (Machine Learning Assignment : Spam SMS Detection)

# Task Objective
This project aims to develop a machine-learning model to detect spam messages in SMS text data. It utilizes natural language processing (NLP) techniques and a supervised learning algorithms to classify SMS messages as either spam or non-spam (ham).

# Dataset
The dataset used for this project is the "SMS Spam Collection" from the UCI Machine Learning Repository. It contains a collection of 5,574 SMS messages, labeled as spam or ham. The dataset can be downloaded from [link to dataset] 

(https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

The dataset file (sms_spam_dataset.csv) contains two columns:
  - label: Indicates whether the message is spam (1) or ham (0).
  - text: The actual text content of the SMS message.
    
# Requirements
To run the project, you need the following dependencies:
 - Google Colab
 - pandas
 - numpy
 - scikit-learn
 - nltk (Natural Language Toolkit)
 - matplotlib
You can install the required packages by running the following command:
```bash
pip install pandas numpy scikit-learn nltk matplotlib
```


# Usage
1. Clone the repository or download the project files.

2. Place the `sms_spam_dataset.csv` file in the project directory.

3. Run the `sms_spam_detection.ipynb` file to train and evaluate the spam detection model.

4. The script will load the dataset, preprocess the text data, and train a machine learning model using the TF-IDF (Term Frequency-Inverse Document Frequency) technique.

5. After training, the model will be evaluated on a holdout set and the performance metrics (such as accuracy, precision, recall, and F1-score) will be displayed.

6. Finally, you can use the trained model to predict the label (spam/ham) of new SMS messages by modifying the predict function in the script.
# Results
The trained model achieved an accuracy of **97.13 %** and Precision is **100 %** on the test set and performed well in terms of precision, recall, and F1-score using Naive Bayes Model.

| Metric  | Score |
|---------|-------|
|Accuracy | 97.13 |
|Precision| 100   |
|Recall   | 80    |
|F1-Score | 89    |

---
The trained model achieved an accuracy of **94.98 %** and Precision is **96 %** on the test set and performed well in terms of precision, recall, and F1-score using LogisticRegression Model.

| Metric  | Score |
|---------|-------|
|Accuracy | 94.98 |
|Precision| 96    |
|Recall   | 65    |
|F1-Score | 78    |

---
The trained model achieved an accuracy of **97.58 %** and Precision is **100 %** on the test set and performed well in terms of precision, recall, and F1-score using RandomForsetClassifier Model.

| Metric  | Score |
|---------|-------|
|Accuracy | 97.58 |
|Precision| 100   |
|Recall   | 82    |
|F1-Score | 90    |

---

Feel free to contribute, modify, or use the code according to the terms of the license.
# Contact
If you have any questions or suggestions regarding the project, feel free to contact Kishan Patel at prasanthipoka@gmail.com
