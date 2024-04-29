# Naive Bayes Text Classification with Sentiment Analysis
This Colab notebook demonstrates a from-scratch implementation of Naive Bayes for text classification with sentiment analysis. The goal is to classify sentences into one of five sentiment categories: very negative, negative, neutral, positive, or very positive.

## Dataset
The dataset is sourced from the Stanford Sentiment Treebank (SST), a collection of movie reviews labelled with sentiment score(a realvalue)and some other annotations thatare irrelevant to the usecase.
## Preprocessing
The dataset consists of text samples that are scored on a scale from 0 to 1, representing the sentiment expressed within each sample. Sentiment classification was performed by categorizing these text samples into five distinct classes.<br>
The scores are mapped as mentioned below:
* From 0 to 0.2 (0.2 included) will be class 0 “very negative”. 
* From 0.2 to 0.4 (0.4 included) will be class 1 “negative”. 
* From 0.4 to 0.6 (0.6included)will be class 2 “neutral”.
* From 0.6to 0.8 (0.8 included)will be class 3 “positive”.
* From 0.8to 1.0(1.0included)will be class 4 “very positive”.
* 
## Getting Started
To get started, open the notebook in Google Colab. Make sure to enable GPU acceleration for faster processing if available.

## Usage
Training: The notebook contains code for training the Naive Bayes model from scratch using the SST dataset. This involves preprocessing the data, calculating probabilities, and training the model.
Testing: Once the model is trained, you can test it on new sentences to classify their sentiment.
## How to Use
Open the notebook in Google Colab.
Follow the instructions provided in the notebook cells to execute each step.
Feel free to modify the code and experiment with different parameters or datasets.
## Model Comparison
To assess the performance of the from-scratch Naive Bayes implementation, we compare it with the Naive Bayes implementation available in the scikit-learn library.

### Performance Metrics
We evaluate both models using accuracy, precision, recall, and F1-score.

### Results
The results of the comparison are presented in the notebook.
## Requirements
* Python 3.x
* Google Colab or Jupyter Notebook
* Libraries: numpy, CountVectorizer, accuracy_score
## Acknowledgments
This implementation is based on the principles of Naive Bayes classification and sentiment analysis. Credits to the creators of the SST dataset and contributors to the libraries used.
