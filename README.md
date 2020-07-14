# Tweets emotions classification using word2vec

### Subtasks

1. **Data Representation**

A. Aquire emotioanl texts dataset: [Download Link](https://github.com/bfelbo/DeepMoji/raw/master/data/PsychExp/raw.pickle) and use 80%/20% train/test split.   
Labels are arranged in the following way: [joy, fear, anger, sadness, disgust, shame, guilt]  

B. Build a representation of words using pre-trained Word2Vec word vectors 

C. Build a sentence representation: Average word-vectors in a sentence.
*Expected outcome:* Representation of sentences that can be used to feed the neural network 

2.  **Classifier building**. Build an MLP network using Tensorflow to classify sentences

*Expected outcome:* Neural Network Model that can predict Emotions based on the text. 

3. **Validation**. Validate the trained model using data acquired from Twitter and analyse obtained predictions. Validation dataset was scprapped by hashtags resembling emotional labels. 
