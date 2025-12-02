# NLP Basics: Text Preprocessing & Bag of Words

This project demonstrates fundamental Natural Language Processing (NLP) techniques using Python. It covers text preprocessing steps and implements a Bag of Words model.

## 📂 File Description
- **NLP_01.ipynb**: A Jupyter Notebook containing code for text analysis, cleaning, and feature extraction.

## Key Concepts Covered
The notebook implements the following NLP pipeline:
1.  **Tokenization**: Converting paragraphs into sentences and words using `nltk.sent_tokenize` and `nltk.word_tokenize`.
2.  **Stemming**: Reducing words to their root form using `PorterStemmer` (e.g., "playing" -> "play").
3.  **Lemmatization**: Converting words to their base meaningful form using `WordNetLemmatizer` (e.g., "goes" -> "go").
4.  **Stopword Removal**: Filtering out common English words (like "is", "the", "in") to focus on meaningful text.
5.  **Text Cleaning**: Using Regular Expressions (`re`) to remove non-alphabetic characters and convert text to lowercase.
6.  **Bag of Words (BoW)**: Converting the cleaned text corpus into a numerical vector representation using `sklearn.CountVectorizer`.

## 🛠️ Dependencies
The following libraries are used in this project:
- `nltk` (Natural Language Toolkit)
- `scikit-learn` (for CountVectorizer)
- `re` (Regular Expressions)

## 📝 Usage
To run the notebook, ensure you have the necessary libraries installed:
```bash
pip install nltk scikit-learn
