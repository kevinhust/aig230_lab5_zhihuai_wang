
# NLP Assignment 5 - Text Preprocessing and Word Embeddings

This project is for my AIG 230 NLP class. I worked on a text pipeline using Python to clean up a book and then turn the words into numbers (vectors).

## What I Did

### Part A: Cleaning the Text
I used **NLTK** to process the book *Alice in Wonderland*. I did things like:
- Turning everything to lowercase.
- Removing punctuation and grammar signs.
- Getting rid of "stop words" (like 'the', 'is', 'at').
- Using lemmatization to get the base form of words.

### Part B: Turning Text into Math
I used **scikit-learn** to represent the text in two ways:
1. **Bag-of-Words (BoW)**: Just counting how many times words show up.
2. **TF-IDF**: A way to see which words are actually important in a sentence.
I also used cosine similarity to find which sentences in the book are the most similar.

### Part C: Word Embeddings
I trained a **Word2Vec** model using **Gensim**. 
- I checked which words are "close" to each other (like 'alice', 'queen', etc.).
- I also tried some word analogies (like `queen - king + alice`). It's pretty cool to see how the model learns relationships even with a small book.

## Tools I Used
- **NLTK** for the basic text stuff.
- **Scikit-learn** for the vectorizing.
- **Gensim** for the Word2Vec model.
- **Pandas/NumPy** for handling the data.

## How to Run It
1. Install everything in `requirements.txt`.
2. Open `A5_Assignment_NLP.ipynb` and run the cells!

