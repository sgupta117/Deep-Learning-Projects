# Long Short Term Memory
 - Word Embedding : The main advantage of using word embedding is that it allows words of similar context to be grouped together and dissimilar words are positioned far away from each other. 
This is done with the help of an Embedding Matrix.
The similarity of 2 words can be found with the help of Cosine Similarity.
Word embedding is a popular technique of converting sparse representation vectors into dense smaller vectors. This increases computation times by a significant factor and saves resources.
It is an improvement over the traditional bag-of-word model encoding schemes where large sparse vectors were used to represent each word or to score each word within a vector to represent an entire vocabulary. These representations were sparse because the vocabularies were vast and a given word or document would be represented by a large vector composed mostly of zero values.

Instead, in an embedding, words are represented by dense vectors where a vector represents the projection of the word into a continuous vector space.
The position of a word within the vector space is learned from text and is based on the words that surround the word when it is used.

 - Fake News Classifier
 - Stock Price Prediction

https://machinelearningmastery.com/use-word-embedding-layers-deep-learning-keras/
https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21
https://www.kaggle.com/thebrownviking20/intro-to-recurrent-neural-networks-lstm-gru

The Problem, Short-term Memory
Recurrent Neural Networks suffer from short-term memory. If a sequence is long enough, they’ll have a hard time carrying information from earlier time steps to later ones. So if you are trying to process a paragraph of text to do predictions, RNN’s may leave out important information from the beginning.
During back propagation, recurrent neural networks suffer from the vanishing gradient problem. Gradients are values used to update a neural network's weights. 
 
The vanishing gradient problem is when the gradient shrinks as it back propagates through time. If a gradient value becomes extremely small, it doesn’t contribute too much learning.

