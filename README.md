# Natural-Language-Processing
Here, I have discussed some techniques of converting a text, which could be a word or a sentence, to a d-dimensional vector. The discussed techniques are given below:
- Bag of Words(BoW)
- TF(Term Frequency)
- IDF(Inverse Document Frequency)
- Word to Vector(Word2Vec)
- Average Word to Vector(Avg Word2Vec)
- TF-IDF Weighted Word2Vec

Hands-on experience of all the above listed techniques can be found out in this [notebook](https://github.com/deveshSingh06/Amazon-Fine-Food-Reviews-Analysis/blob/master/Amazon%20Fine%20Food%20Reviews%20Analysis.ipynb) (from section 4 through section 9).


I have also discussed some text pre-processing techniques such as:
1. Stop-words removal
2. Lower case conversion
3. Stemming
4. Lemmitization

## Why convert text to a vector?
- Converting a text to a vector helps us use the power of linear algebra.
- Using linear algebra we can find out the distances between different vectors corresponding to different texts.
- This could help us classify various groups of texts such as positive and negative texts. Or we can find out the sentiment polarity of a document.

> **Note:** 1. A text, which could be a word or a sentence, is known as a document in NLP.
        2. A collection of such documents is known as document corpus.
