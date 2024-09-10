# NLP Intent Classification and Named Entity Recognition Project

## Overview

This project involves building a general-purpose assistant that detects user intents and extracts relevant entities. It aims to classify intents from various user requests and identify whether some intents are out of scope (OOS). The project also covers topic modeling and entity recognition using the Spacy library.

## Project Structure

The project is divided into six main parts:
1. **Exploratory Data Analysis (EDA)**: Analyze the dataset and extract insights such as word distributions, class counts, and average sentence length.
2. **Data Preparation**: Process the sentences by removing stop words, punctuation, and applying lemmatization. Separate out-of-scope intents from the dataset.
3. **Topic Modeling**: Use TF-IDF and Latent Semantic Analysis (LSA) to uncover hidden topics and compare them with the original intents.
4. **Classification**: Build and evaluate classifiers (Logistic Regression) using bag-of-words and TF-IDF approaches to identify the best model.
5. **Named Entity Recognition (NER)**: Implement NER for specific intents, recognizing entities such as languages, dates, and countries.
6. **Chatbot Simulation**: Create a simple chatbot that detects user intent and responds with generic answers.

## Installation

To run the project, you need Python 3.x and the required libraries. Install the necessary dependencies by running the following command:

```bash
pip install -r requirements.txt
```

Additionally, you need to download the Spacy language model by running:

```bash
python3 -m spacy download en_core_web_md
```