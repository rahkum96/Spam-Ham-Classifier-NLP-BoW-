# Spam-Ham-Classifier-NLP-BoW

![image](https://user-images.githubusercontent.com/86415241/134724061-3c8f8cba-cb9c-4501-81e6-b436d3e52c43.png)

### About
Email Spam Detection – A Comparative Analysis of Machine Learning Models. My Model will classify wheather the Email is spam or not. We used a shuffled sample of email subjects and body that contained both spam and ham emails in various proportions and were transformed into lemmas. Email Spam Detection is one of the most productive Deep Learning projects, but it's also one where people lose faith in their ability to find the simplest model for accuracy. In this post, we'll evaluate four alternative strategies for detecting spam in emails and determining the best accurate model.


### Data Preparation
- Download spam and ham emails through Kaggle links are given below.
- Converted the lists to data frames, joined the spam and ham data frames, and shuffled the resultant data frame.
- Split the data frame into train and test data frames. The test data was 20% of the original dataset.
- Split the mail text into lemmas and applied TF-IDF transformation using CountVectorizer followed by TF-IDF transformer.
- Trained four models using the training data:
   **Naive Bayes**
- The email label for the test dataset was predicted using the trained models. Accuracy, Precision, Recall, and F1-score were calculated as four measures to assess the models' performance.

### Models with their Accuracy of Prediction
Model accuracy is 97.7%

           
           precision    recall  f1-score   support

           0       0.97      1.00      0.99       955
           1       1.00      0.84      0.91       160


### NOTE
==> Python version 3.9.0 was used for the project.

==> You can find all the model https://github.com/rahkum96/Spam-Ham-Classifier-NLP-BoW-/blob/main/Spam_classifier.ipynb


### Steps to run this model in your system
1. Clone or download the repo.
2. Open command prompt in the downloaded folder.



### Dataset link
https://www.kaggle.com/uciml/sms-spam-collection-dataset

