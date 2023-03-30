# Toxic-Comments-Classifier
Created a web app which will classify comments into 6 different classes (Multi Label). Used NLP preprocessing techniques and ML &amp; DL models for training.

## Problem Statement :
The prevalence of online toxicity has become a growing concern in social media platforms, and it can negatively impact individuals and communities. In this project, i have worked with a toxic comment classification dataset that includes comments labeled with multiple toxic classes, and used Natural Language Processing (NLP) techniques to build a multilabel predictive model.

Algorithms Used :- Logistic Regression, Decision Tree, Random Forest,  Multinomial Naive Bayes, XGBoost, LightGBM, Gradient Boost, RNN, LSTM, GRU.

### Project Steps

1) Exploration of data using pandas, numpy, matplotlib and plotly.

![Screenshot (64)](https://user-images.githubusercontent.com/55007875/228819346-59b8a2dd-8870-4555-8d87-b7222b693c9e.png)

2) Data Preprocessing :- Tried varies data preprocessing techniques 
- Contraction
- Removing punctuations and unwanted characters using regex
- Removing Stopwords
- Lemmatization
- TFIDF Vectoizer
- Word to vec

3) Modelling :- Impllemented various machine learning and deep learning models
- Logistic Regression
- Decision Tree
- Random Forest
- Multinomial Naive Bayes
- XGBoost
- LightGBM
- Gradient Boost
- RNN
- LSTM
- GRU

4) Performed Hyper parameter tuning for XGBoost using GridSearchCV
5) Models Comparison
- Based on Accuracy
 ![accuracies](https://user-images.githubusercontent.com/55007875/228821411-383dbcdc-dd66-4f19-8f83-8aab6ab4be93.png)
- Basid on Hamming Loss
![hamming_loss](https://user-images.githubusercontent.com/55007875/228821459-91c64c89-1133-42a4-8f07-5780b438a80a.png)
- Based on Log Loss 
![logg_loss](https://user-images.githubusercontent.com/55007875/228821530-04332a17-33fe-401d-9ff3-032fbba1ca27.png)



