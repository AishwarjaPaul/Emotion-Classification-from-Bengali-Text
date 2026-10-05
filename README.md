# Sentiment Analysis in Bengali Text using NLP

## Overview
This repository contains the implementation of an undergraduate thesis on emotion classification in Bengali text using machine learning and deep learning approaches.

The study investigates Bengali emotion detection using traditional machine learning models, recurrent neural networks, and transformer-based language models.

## Dataset
The research uses **BANEmo**, a manually annotated Bengali text dataset containing **14,999 samples** collected from online sources.

The final emotion categories include:
- Happiness
- Sadness
- Exasperation
- Fear
- Others

## Models Implemented
The following approaches were evaluated:

- Multinomial Naive Bayes
- Support Vector Machine (SVM)
- Bidirectional LSTM (BiLSTM)
- BanglaBERT

Text representations and embeddings used include:
- Bag-of-Words (BoW)
- TF-IDF
- GloVe embeddings

## Methodology
The workflow includes:

- Bengali text collection and annotation
- Text preprocessing
- Exploratory data analysis
- Feature extraction
- Machine learning model development
- Deep learning model development
- Transformer fine-tuning
- Model evaluation and comparison

## Results
Among the evaluated approaches, fine-tuned **BanglaBERT** achieved the best performance with an accuracy of approximately **69.2%**.

## Technologies
- Python
- Scikit-learn
- PyTorch
- Hugging Face Transformers
- Keras
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Research Output
This work was later extended into the paper:

**“Emotion Detection in Bengali Text Using Machine Learning and Deep Learning Models: A Study with the BANEmo Dataset”**

Accepted at the **16th IEEE International Conference on Computing, Communication and Networking Technologies (ICCCNT), 2025**.

## Contributors
- Aishwarja Paul Sourav
- Ankon Sarkar
- Rezvi Ahmed

## Academic Context
Undergraduate Thesis  
Department of Computer Science and Engineering  
BRAC University
