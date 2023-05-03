# Fake News Classifier

This project is a machine learning model that can classify news articles as either real or fake. The model was built using a dataset of news articles with labels indicating whether each article was real or fake.

## Getting Started

To use this model, you will need to install Python and several Python libraries, including pandas, numpy, scikit-learn, and nltk. You can install these libraries using pip:

```pip install pandas numpy scikit-learn nltk```

## Usage

To use the model, you can run the fake_news_classifier.py script. This script loads the dataset, preprocesses the text data, trains the machine learning model, and outputs the model's accuracy, precision, recall, and F1 score. You can also generate predictions for new news articles using the model.

## Dataset

The dataset used in this project is available on Kaggle at [Dataset](https://www.kaggle.com/c/fake-news/data). The dataset consists of news articles with labels indicating whether each article is real or fake.

## Model

My model is a machine learning algorithm trained to predict whether a given news article is fake or real. It uses a dataset of news articles, with labels indicating whether each article is real or fake, to learn patterns and make predictions on new, unseen data.

I used a variety of natural language processing techniques to preprocess and clean the data, including tokenization, removing stop words, and lemmatization. I then used a bag-of-words approach to convert the text data into numerical features that could be used in our machine learning model.

Our model achieved an accuracy score of 0.96 on a held-out test set, meaning it correctly classified 96% of the articles as either real or fake. We also calculated precision, recall, and F1 scores to evaluate the model's performance and found that it performed well across all metrics.

Overall, our model's success in classifying news articles as real or fake demonstrates the potential for machine learning algorithms to assist in identifying and combating the spread of misinformation and fake news online.

Metric	Scores:
Accuracy	0.964
Precision	0.970
Recall	0.964
F1 Score	0.967

![Confusion_Matrix](https://user-images.githubusercontent.com/80132877/235818579-100e93bd-2b4d-46d9-8286-eef6510ac5d5.png)

## Acknowledgments

This project was inspired by the Fake News Challenge
