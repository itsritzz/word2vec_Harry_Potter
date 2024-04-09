# Harry Potter Text Analysis with Word2Vec

This project aims to perform a detailed text analysis on the Harry Potter novel series. Leveraging the Word2Vec model from the `gensim` library, we explore the contextual relationships between words in the magical universe created by J.K. Rowling. Our analysis includes preprocessing the text data to remove noise, building and training a Word2Vec model, and finally, probing the model to uncover interesting word associations and similarities.

## Dependencies

The project relies on several Python libraries. Ensure you have the following dependencies installed:

- `pandas`: For data manipulation and analysis.
- `gensim`: For using the Word2Vec model.
- `nltk`: For text preprocessing, including stop word removal and sentence tokenization.

## Project Structure

- **Harry Potter Data/**: A directory that contains the text files of the Harry Potter novels. Each file corresponds to a single book in the series.
- **analysis.py**: The Python script that houses all the code for text preprocessing, Word2Vec model training, and analysis of word relationships.

## Features

### Text Preprocessing

Text preprocessing is vital in natural language processing (NLP). In this project, we:
- **Remove punctuation** from the text, since punctuation marks do not contribute to word context.
- **Filter out English stop words** (e.g., "the", "is", "in") as they are common across all texts and do not offer valuable insights.

### Word2Vec Model

We utilize the `gensim` library's implementation of Word2Vec to:
- **Build a vocabulary** from the preprocessed text.
- **Train a model** to generate word embeddings, capturing the essence of word relationships based on their context within the Harry Potter series.

### Analyzing Word Relationships

With the trained Word2Vec model, we can:
- **Identify words** that are most similar to a given word.
- **Determine the odd one out** from a list of words.
- **Explore the vector representation** of words to understand how the model perceives different characters, objects, and concepts from the novels.
- **Assess the similarity** between two words to understand their contextual relationship.

## Contributing

Feel free to fork the project, make changes, and submit pull requests. Contributions are welcome!

