# Project Overview
This project focuses on predicting the next word in a sentence using N-gram models, a fundamental technique in natural language processing (NLP). By leveraging a dataset of dialogs, the project aims to build probabilistic models that capture word co-occurrences and can predict the most likely next word based on preceding words.
## Dataset
The dataset consists of dialogs that are cleaned to remove non-alphabetic characters and converted to lowercase for uniformity. This preprocessing step ensures that the N-gram models accurately capture the language patterns present in the dialogs.
## Techniques Used
1. N-gram Modeling: 
   - Unigrams: Single-word sequences.
   - Bigrams: Two-word sequences.
   - Trigrams: Three-word sequences.
   2. Probabilistic Modeling: 
   - The project builds a probabilistic model using the N-grams to predict the probability distribution of the next word given the previous words in a sequence.

## Results

The developed model successfully predicts the next word in a sentence based on the learned probabilities from the dialogs dataset. 
