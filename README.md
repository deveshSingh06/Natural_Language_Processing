# Natural-Language-Processing
Here, I have discussed some techniques of converting a text, which could be a word or a sentence, to a d-dimensional vector. The discussed techniques are given below:
- Bag of Words(BoW)
- TF(Term Frequency)
- IDF(Inverse Document Frequency)
- Word to Vector(Word2Vec)
- Average Word to Vector(Avg Word2Vec)
- TF-IDF Weighted Word2Vec

I have also discussed some text pre-processing techniques such as:
1. Deduplication
2. Stop-words removal
3. Lower case conversion
4. Stemming
5. Lemmitization

## Why convert text to a vector?
- Converting a text to a vector helps us use the power of linear algebra.
- Using linear algebra we can find out the distances between different vectors corresponding to different texts.
- This could help us classify various groups of texts such as positive and negative texts. Or we can find out the sentiment polarity of a document.

> **Note:** 1. A text, which could be a word or a sentence, is known as a document in NLP.
        2. A collection of such documents is known as document corpus.
