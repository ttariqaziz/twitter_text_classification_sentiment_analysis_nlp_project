# twitter_text_classification_nlp
## Overview
The COVID-19 pandemic has had a significant impact on society, and the need for accurate and
reliable information has never been greater. In this project, we propose to use natural language
processing (NLP) techniques to classify text data related to COVID-19.
This project will use [open-source data](https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification) data of the year 2020 from Twitter, which includes thousands of text snippets from various sources such as news articles, social media posts, and government documents.
## Goal
The objective of this project is to build a model that can accurately classify text data into
different categories related to COVID-19, such as information about symptoms, treatments, and
vaccines. The model will be trained on the dataset mentioned above and will be evaluated
based on its ability to classify unseen text data.
## Methodology
The first step in this project will be to preprocess the text data, which will involve cleaning and
normalizing the text, as well as removing any irrelevant information. Next, we will use various
NLP techniques such as tokenization, stemming, and vectorization to prepare the text data for
modeling. We will then use machine learning algorithms such as logistic regression, naive
Bayes, Random Forest, and SVM to train the model.
## Evaluation
The performance of the model will be evaluated using metrics such as accuracy, precision, recall and F1 score.
## Project Structure
```
twitter_text_classification_sentiment_analysis_nlp_project
├─ Data
│  ├─ Corona_NLP_test.csv
│  └─ Corona_NLP_train.csv
├─ Data_Wrangling_Exploratory_Data_Analysis.ipynb
├─ New_Data_Wrangling_Exploratory_Data_Analysis.ipynb
├─ Notebook
│  ├─ Capstone_2_Data_Modeling.ipynb
│  ├─ Capstone_2_Data_Modeling_(2).ipynb
│  └─ Data_Modeling_Final_Version.ipynb
├─ Plots
│  ├─ Hashtags.png
│  ├─ Model Comparison Table.png
│  ├─ NB Confusion Matrix.png
│  ├─ Negative-Tweets-Wordcloud.png
│  ├─ Neutral-Tweets-Wordcloud.png
│  ├─ No of Characters in Tweets.png
│  ├─ No of Words in a Tweet.png
│  ├─ Pie Chart of Sentiments.png
│  ├─ Positive-Tweets-Wordcloud.png
│  ├─ RF Confusion Matrix.png
│  ├─ SGDC Confusion Matrix.png
│  ├─ Test Missing Values.png
│  ├─ Test Sentiment Analysis-1.png
│  ├─ Test Sentiment Analysis.png
│  ├─ Top 10 Tweet Locations.png
│  ├─ Train Missing Values.png
│  ├─ Train Sentiment Analysis-1.png
│  ├─ Train Sentiment Analysis.png
│  ├─ Train Test Comparison.png
│  ├─ Tweets Timeline-1.png
│  └─ Tweets Timeline.png
├─ README.md
├─ Twitter NLP Text Capstone # 2 Presentation.pdf
├─ Twitter NLP Text Capstone # 2 Report .pdf
└─ Updated_Data_Wrangling_Exploratory_Data_Analysis.ipynb
```

<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/Pie%20Chart%20of%20Sentiments.png">
<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/Top%2010%20Tweet%20Locations.png">
<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/Hashtags.png">
<img src ="https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/No%20of%20Words%20in%20a%20Tweet.png">
<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/Positive-Tweets-Wordcloud.png">
<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/Negative-Tweets-Wordcloud.png">
<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/Neutral-Tweets-Wordcloud.png">

## Model Accuracy Comparison
<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/Model%20Comparison%20Table.png">

## Confusion Matrices
<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/RF%20Confusion%20Matrix.png">
<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/NB%20Confusion%20Matrix.png">
<img src = "https://github.com/ttariqaziz/twitter_text_classification/blob/main/Plots/SGDC%20Confusion%20Matrix.png">

