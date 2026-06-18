# Arabic Fake News Detection

## Overview

This project focuses on detecting fake news articles written in Arabic using Natural Language Processing (NLP) and Machine Learning techniques.

The dataset contains Arabic news articles labeled as either real or fake. Several preprocessing techniques were applied to prepare the text before training classification models.

## Dataset

* Total Articles: 5,352
* Real News: 3,913 (73.11%)
* Fake News: 1,439 (26.89%)

## Data Preprocessing

The following preprocessing steps were applied:

* Arabic text normalization
* Removal of diacritics
* Removal of punctuation and numbers
* Stopword removal
* Arabic stemming using ISRIStemmer
* TF-IDF feature extraction

## Machine Learning Models

Three machine learning models were trained and evaluated:

### Logistic Regression

Accuracy: 88.98%

### Random Forest

Accuracy: 88.80%

### Support Vector Machine (SVM)

Accuracy: 90.29%

## Results

The SVM classifier achieved the best overall performance with an accuracy of approximately 90.3%.

Model comparison:

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 88.98%   |
| Random Forest       | 88.80%   |
| SVM                 | 90.29%   |

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* TensorFlow / Keras
* Matplotlib
* Seaborn

## Project Type

Academic NLP project developed as part of Data Science and Artificial Intelligence studies.

## Open in Google Colab

🔗 Google Colab Notebook:
[https://colab.research.google.com/drive/12hJrJufV4wCgnEDkfceEfLtADgkfJU8x](https://colab.research.google.com/drive/12hJrJufV4wCgnEDkfceEfLtADgkfJU8x?usp=sharing)

## Author

Nagham Zidiah
