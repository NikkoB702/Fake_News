# Fake News Classifier

Fake news has become a major issue in today's world. The spread of false information can have serious consequences, from misleading people to influencing important decisions. With the rise of social media and the ease of sharing information online, it has become increasingly difficult to distinguish between true and false information.

This is where a model like the one we've created can be extremely beneficial. By using machine learning algorithms to identify patterns and features that distinguish between fake and real news, we can create a tool that can help individuals and businesses to verify the accuracy of news articles.

For individuals, a model like this can be used as a browser extension or app that can flag articles that are likely to be fake news. This can help individuals make informed decisions about what they read and share on social media.

For businesses, a model like this can be an important tool for reputation management. In today's digital age, businesses are increasingly vulnerable to negative publicity, and fake news can spread quickly and damage a company's reputation. By using a model like this to quickly identify and respond to fake news articles that mention their brand, businesses can protect their reputation and mitigate the damage caused by false information.

Overall, a model like this has the potential to benefit both individuals and businesses by helping them to identify and avoid false information. By leveraging the power of machine learning, we can create tools that make it easier to navigate the complex world of news and information in the digital age.
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


![Scores](https://user-images.githubusercontent.com/80132877/235819319-e7e799d0-9c4b-4f40-b13e-0fe7f94e3d93.png)

![Confusion_Matrix](https://user-images.githubusercontent.com/80132877/235818579-100e93bd-2b4d-46d9-8286-eef6510ac5d5.png)

## Acknowledgments

This project was inspired by the Fake News Challenge
