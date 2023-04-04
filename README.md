# nlp-experiments

1. Contradictory My Dear Watson BERT base BSC Function.ipynb - I try to predict whether two sentences form a contradiction, entailment or neutral pair using bert base uncased model. The model I use to classify is imported with a wrapper by huggingface bertsequentialclassifier. I was able to achieve 61% accuracy in 5 epochs. Using this baseline, I will try to measure accuracy of my custom model.

2. Contradictory My Dear Watson BERT base custom function.ipynb - I try to predict the same as point 1 but this time by building my own edition of huggingface bertsequentialclassifier. I was able to achieve 70.5% accuracy in 10 epochs.

3. Word Vectorization Techniques.ipynb - Goal is to try different word vectors like, tfidf vectors, word2vec, glove, bert, etc. to test if they can provide a way to classify news articles into 5 unique categories.
