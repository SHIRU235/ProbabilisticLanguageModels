# ProbabilisticLanguageModels
#  Probabilistic Language Models with NLTK

This project implements **Unigram** and **Bigram language models** using the NLTK-provided **Gutenberg Corpus**. The models are designed to estimate sentence probabilities, apply Laplace smoothing, and build inverted indexes for information retrieval tasks.

---

## Dataset Description

We use the [**Gutenberg Corpus**](https://www.nltk.org/nltk_data/) from the [Natural Language Toolkit (NLTK)](https://www.nltk.org/) which contains 18 classic English literary texts from authors like:

- Jane Austen
- William Shakespeare
- Herman Melville
- And more

Each document is processed through:
- Lowercasing and tokenization
- Stopword removal and stemming (Porter Stemmer)
- Construction of:
  - Vocabulary
  - Inverted index
  - Unigram and Bigram models with Laplace smoothing Log Probability

---

##  Team Members

## Team 9

Name – Shiranth Stephen Sahaya Anbu Anitha,  Student ID: 8961999
Name - Bhupender Sejwal, Student ID: 9044574


---

##  Dataset and License

-  **Dataset**: Gutenberg Corpus via NLTK  
  ➤ Downloaded using:  
  ```python
  import nltk
  nltk.download('gutenberg')

  License: Public domain texts
➤ Official source: https://www.gutenberg.org/
➤ NLTK Gutenberg details: https://www.nltk.org/nltk_data/

## Inference Results ##
Query Score (Unigram): -23.0179
Bigram log-probability score: -20.3374
Docs containing 'scienc': [3, 8, 9, 10, 11, 12, 13, 17]
Laplace-smoothed bigram probability for the sentence: 0.0030959752
Laplace-smoothed bigram log-probability: -5.7777