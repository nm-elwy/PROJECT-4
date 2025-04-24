## Apple vs Google: A Comparative Sentiment Analysis in Tweets Related to Apple and Google Products
### Project Overview
Social media platforms like Twitter provide a great amount of realtime insights into customer opinions, especially regarding products and services. For tech gaints like Apple and Google, monitoring sentiments around their products can be a crucial business strategy. Understanding how consumers feel about their products or services, whether positively, negatively or neutrally, helps inform marketing strategies, product development and customer support.

This project aims to build a Natural Language Processing (NLP) model to analyse the sentiment of tweets related to Apple and Google Products.
### Contributors
* Bruce Siti: bruce.siti@student.moringaschool.com
* Okech Maxmilian: okech.maximillan@student.moringaschool.com
* Bertha Karuku: bertha.karuku@student.moringaschool.com
* Roy Gichia: roy.gichia@student.moringaschool.com
* Mich Sego: mich.sego@student.moringaschool.com
* Neema Elaly: neema.elaly@student.moringaschool.com
### Tech Stack
* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Tensorflow/Keras
* NLTK
* VADER
### Data Understanding
The dataset is from CrowdFolder via data.world. The dataset consists of over 9,000 tweets that have been rated by human annotators as positive, negative or neutral sentiment.
### Objectives
* Preprocess tweet data effectively through removing noise, handling stopwords and tokenization, to improve model accuracy.
* Identify patterns in customer sentiments towards Apple and Google products.
* Build and evaluate multiple machine learning and deep learning models to classify tweet sentiments.

### Data Analysis
The text data from the tweets was cleaned, analysed, tokenised, lemmatised and vectorised using TF-IDF. VADER was used to analyse sentiments of the text.
### Modeling
For this project, the following models were trained:
* Logistic Regression
* Random Forest
* Multiclass Neural Network
* LSTM - Long-short Term Memory
### Conclusion/Next Steps
LSTM demonstrated the highest effectiveness in understanding language in a better way, making it the most suitable model for sentiment analysis on social media text. Future enhancements could include more training data, use of pre-trained embeddings like GloVe or BERT, or expanding into bidirectional LSTMs for even deeper context learning.
### Repository Structure
**README.md:** This file provides an overview of the project.

**Sentiment Analysis.pptx**: Contains a non-technical presentation on the project.

**Notebook**: Notebooks with information on data cleaning, analysis, visualisation and modeling.

**Data**: Contains a csv file with the dataset used for analysis.

**abbr.text** : Contains a text file of all the abbrevations considered in the analysis.
### How to Use This Repository
* Fork the repository.
* Clone the repository.
* Navigate to the project directory.
* Download and install the necessary dependencies.
* Open and run the notebook in an IDE of your choice. **Jupyter Notebooks** is recommended.
