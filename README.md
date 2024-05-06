# Topic-Modeling-with-Latent-Dirichlet-Allocation-LDA-

### README

#### Topic Modeling with Latent Dirichlet Allocation (LDA)

This repository contains code for performing topic modeling on textual data using Latent Dirichlet Allocation (LDA). The code preprocesses the text data, tokenizes it, removes stop words, identifies bigrams and trigrams, performs lemmatization, and finally applies LDA to discover latent topics within the corpus.

#### Prerequisites

Ensure Python is installed on your system along with the required libraries:

- pandas
- numpy
- gensim
- nltk
- spacy

You can install these libraries using pip:

```bash
pip install pandas numpy gensim nltk spacy
```

#### Usage

1. Clone or download the repository.
2. Place your text data file (e.g., JSON, CSV) in the same directory as the code.
3. Update the file path in the code to point to your data file.
4. Execute the code using a Python interpreter.
5. Follow the instructions provided in the code comments to preprocess the data and train the LDA model.
6. Experiment with different parameters such as the number of topics and the preprocessing steps to optimize the model.

#### Features

- Preprocesses textual data by removing emails, new line characters, and non-alphabetic characters.
- Identifies and removes stop words and tokenizes the text.
- Applies bigram and trigram detection to capture multi-word expressions.
- Performs lemmatization to reduce words to their base forms.
- Implements LDA using the Gensim library to discover topics within the corpus.
- Evaluates model performance using perplexity and coherence score metrics.

