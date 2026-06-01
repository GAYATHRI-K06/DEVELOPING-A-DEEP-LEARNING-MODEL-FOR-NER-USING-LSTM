# DEVELOPING-A-DEEP-LEARNING-MODEL-FOR-NER-USING-LST
DL- Developing a Deep Learning Model for NER using LSTM
## AIM
To develop an LSTM-based model for recognizing the named entities in the text.

## Problem Statement and Dataset
Named Entity Recognition (NER) is a fundamental task in Natural Language Processing (NLP) that involves identifying and classifying entities such as person names, organizations, locations, dates, and other predefined categories from unstructured text data. Traditional rule-based and statistical approaches often struggle with handling contextual dependencies and sequential information in sentences.

The objective of this project is to develop a Deep Learning-based Named Entity Recognition model using Long Short-Term Memory (LSTM) networks. The model should be capable of learning contextual relationships within sequences of words and accurately predicting entity labels for each token in a sentence.

The system will take annotated text data as input, preprocess it into suitable numerical representations (such as word embeddings), and train an LSTM model to perform sequence labeling. The performance of the model will be evaluated based on metrics such as accuracy, precision, recall, and F1-score.

The developed model aims to improve entity recognition performance by leveraging the sequential learning capability of LSTMs and handling long-range dependencies in text.

## DESIGN STEPS
**STEP 1:**
Load data, create word/tag mappings, and group sentences.

**STEP 2:**
Convert sentences to index sequences, pad to fixed length, and split into training/testing sets.

**STEP 3:**
Define dataset and DataLoader for batching.

**STEP 4:**
Build a bidirectional LSTM model for sequence tagging.

**STEP 5:**
Train the model over multiple epochs, tracking loss.


 
## RESULT
Thus, an LSTM-based model for recognizing the named entities in the text has been developed successfully.
