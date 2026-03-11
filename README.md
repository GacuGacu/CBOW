# CBOW Word2Vec — From Scratch Implementation
A from-scratch implementation of the Word2Vec CBOW (Continuous Bag of Words) model using only NumPy, built as part of the JetBrains 2026 internship application.
## What's in here

1. Full preprocessing pipeline (tokenization, vocabulary mapping, training pair generation)
2. CBOW model with manual forward and backward pass.
3. Training loop with cross-entropy loss
4. Word similarity evaluation using cosine similarity

 ## Dependencies
numpy, matplotlib, re

## Reference
The gradient math was derived with reference to this Skip-gram implementation: [Skip-gram implementation](https://jaketae.github.io/study/word2vec/), but adapted for CBOW architecture.

The content of original training text is taken from this wikipedia page: [Word2vec](https://en.wikipedia.org/wiki/Word2vec).
## How to run
Open CBOW.ipynb in Jupyter and run all cells.
