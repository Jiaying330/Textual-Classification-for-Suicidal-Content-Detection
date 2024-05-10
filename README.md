# Enhanced Textual Classification for Suicidal Content Detection

This project explores the use of Recurrent Neural Networks (RNNs) and Attention Mechanisms for classifying textual content from Reddit's "r/SuicideWatch" and "r/teenagers" subreddits. It aims to discern posts expressing suicidal ideation from those unrelated to such concerns, leveraging machine learning models for effective identification.

## Abstract

The increasing volume of user-generated content on social media complicates the manual monitoring of distressing content. This project employs advanced machine learning techniques to automate the detection of suicidal ideations in online posts, facilitating timely interventions. We evaluate various RNN architectures including plain RNN, GRU, and GRU with Attention Mechanism to establish their efficacy in recognizing concerning content.

## Introduction

Online platforms are pivotal in self-expression and support-seeking behaviors, necessitating proactive identification of distress signals, particularly concerning suicide. This study harnesses deep learning and natural language processing to classify posts potentially indicating suicidal thoughts, using sophisticated RNN models to enhance automated monitoring systems on platforms like Reddit.

## Data

The dataset used in this project consists of posts from Reddit's "r/SuicideWatch" and "r/teenagers" subreddits, which include labeled suicidal and non-suicidal posts. This dataset is publicly available on Kaggle and can be accessed [here](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch). It serves as the primary source for training and testing the models, providing a real-world application scenario for textual classification.

## Contributions

- Developed a preprocessing pipeline using Spacy for text manipulation including stopword removal, lemmatization, and tokenization.
- Implemented and evaluated plain RNN, GRU, and GRU with Attention mechanisms to classify textual content into suicidal and non-suicidal.
- Utilized metrics such as accuracy, precision, recall, and f1-score for model evaluation, providing insights into each model's performance.

## Models and Experiments

The project involves:
- **Data Preprocessing**: Text data from selected Reddit posts is cleaned and processed using spaCy.
- **Feature Engineering**: A vocabulary set is created and textual tokens are transformed into numerical representations.
- **Model Training**: Models are trained using configurations suitable for text classification, including attention mechanisms to focus on relevant text segments.

## Results

The evaluation shows:
- GRU models outperform plain RNN in all metrics.
- Attention mechanisms did not significantly enhance performance over plain GRU, possibly due to the simplicity of the dataset.

## Discussion

Further research could explore more complex models and larger, diverse datasets to improve detection capabilities. The current models offer a baseline for developing robust systems for mental health monitoring on social media.

## Citation

For further reference, please consult the original research documentation and related academic papers provided in the project's comprehensive bibliography.
