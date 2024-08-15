# Text Retrieval System
This repository contains the implementation of a text retrieval system using the MS MARCO dataset. The system is designed to return the most relevant documents in response to a given query. It leverages various techniques such as text normalization, vectorization, and similarity calculation to perform efficient document retrieval.


## Overview
The text retrieval system is implemented in Python and is designed to work with the MS MARCO dataset, a large-scale dataset commonly used for question-answering tasks. The system preprocesses the dataset, normalizes the text, and uses the Bag-of-Words model to represent documents and queries as vectors. Cosine similarity is then applied to rank documents based on their relevance to the query.

## Features
- **Text Normalization**: Standardizes text by lowercasing, removing punctuation, and applying stemming.
- **Vocabulary Creation**: Extracts terms from the dataset to create a vocabulary.
- **Vectorization**: Converts text into numerical vectors using the Bag-of-Words model.
- **Document-Term Matrix**: Constructs a matrix where rows represent documents and columns represent terms.
- **Cosine Similarity Calculation**: Measures the similarity between query vectors and document vectors.
- **Query Handling**: Efficiently processes queries and ranks documents based on relevance.
