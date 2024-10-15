# Information Retrieval System

This project implements an information retrieval system using various techniques such as TF-IDF and Word2Vec. The system is designed to search through a large collection of news articles and retrieve relevant documents based on user queries. The full research article writing about information retrieval systems can be found [here](https://github.com/bnm-AI-dev/Information-Retrieval-Models/blob/master/InformationRetrievalModels%20(1).pdf)

## Project Structure

The project consists of several Jupyter notebooks that handle different aspects of the information retrieval process:

1. `DataCleaning.ipynb`: Handles the initial data cleaning and preparation.
2. `EDA.ipynb`: Performs Exploratory Data Analysis on the dataset.
3. `tfidf_Model.ipynb`: Implements the TF-IDF (Term Frequency-Inverse Document Frequency) model.
4. `word2vec.ipynb`: Implements the Word2Vec model for document representation.

## Dataset

The project uses a dataset of news articles split into three files:
- `articles1.csv`
- `articles2.csv`
- `articles3.csv`

The dataset contains approximately 142,570 documents in total, with 99,999 used for training and 42,571 for testing.

## Features

- Data cleaning and preprocessing
- Text normalization (lowercasing, removing punctuation, etc.)
- Stop word removal
- Lemmatization
- TF-IDF vectorization
- Word2Vec model implementation
- Cosine similarity for document ranking

## How to Use

1. Ensure you have all the required libraries installed (pandas, numpy, sklearn, nltk, gensim).
2. Run the notebooks in the following order:
   - `DataCleaning.ipynb`
   - `EDA.ipynb`
   - `tfidf_Model.ipynb` or `word2vec.ipynb` (depending on the model you want to use)

3. Use the search function in the respective model notebook to query the system.

## Model Details

### TF-IDF Model
The TF-IDF model is implemented in `tfidf_Model.ipynb`. It creates a vector space model of the documents and uses cosine similarity to rank documents based on their relevance to the query.

### Word2Vec Model
The Word2Vec model is implemented in `word2vec.ipynb`. It creates dense vector representations of words and documents, allowing for more semantic understanding of the text.

## Future Improvements

- Implement more advanced retrieval models (e.g., BM25, BERT)
- Add a user interface for easier interaction with the system
- Optimize performance for larger datasets
- Implement relevance feedback mechanisms

## Contributors
Brian Mutisyo

## License
MIT License
