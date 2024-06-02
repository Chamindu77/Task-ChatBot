# Chatbot Project

<img src="https://github.com/Chamindu77/Task-ChatBot/assets/117502200/09a876ef-1bc6-4071-9a14-437ee37c5c36" width="550" height="350"/>

## Overview

[![-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](https://github.com/BaseMax?tab=repositories)

In this project, I develop an AI-powered chatbot using BERT, a leading model for natural language understanding. I start by loading and analyzing conversational data, then split it into training, validation, and test sets. I use a pretrained BERT model and tokenizer to convert text data into numerical format and fine-tune the model on my dataset. Finally, I evaluate the chatbot's performance and save the trained model for future use.

[![-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](https://github.com/BaseMax?tab=repositories)

## Table of Contents

- [Data Analysis](#data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Implementation](#model-implementation)
- [Model Evaluation](#model-evaluation)

## Installation

To run the chatbot locally, follow these steps:

1. Colab Link to notebook: [Open in Colab](https://colab.research.google.com/drive/1tPsMeyjbA8yc0ZCXhH3hQwDB5VFi7b66#scrollTo=17a01fHxIFYD)
2. Interact with the chatbot by typing your queries and receiving responses.

## Data Analysis

Before diving into data preprocessing, an essential step is to analyze the dataset to gain insights and understand the distribution of the data. This involves:

- **Exploratory Data Analysis (EDA)**: Conducting a thorough EDA to understand the data's structure, common patterns, and potential outliers.
- **Visualization**: Using visual tools like histograms, bar charts, and word clouds to represent the distribution of different classes, most frequent words, and conversation lengths.
- **Statistical Summary**: Generating summary statistics to evaluate the mean, median, mode, and standard deviation of various features in the dataset.

By performing these analyses, we can identify key characteristics of the conversational data, which will inform the subsequent steps in data preprocessing and model training.

## Data Preprocessing

The dataset used for fine-tuning the pre-trained model underwent preprocessing to ensure quality and relevance. Steps involved in data preprocessing include:

- Data cleaning
- Tokenization
- Lemmatization
- Removing stopwords
- Data augmentation (if applicable)

## Model Implementation

The chatbot utilizes a pre-trained model as its foundation, which was further fine-tuned using the provided dataset. Model implementation includes:

- Loading the pre-trained model
- Fine-tuning the model with the dataset
- Saving the fine-tuned model for deployment

## Model Evaluation

The chatbot's performance was evaluated using various metrics, including:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

The evaluation process helps assess the chatbot's effectiveness in handling user queries and providing accurate responses.
