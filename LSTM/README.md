# Long Short Term Memory
 - Word Embedding
 - Fake News Classifier
 - Stock Price Prediction

https://machinelearningmastery.com/use-word-embedding-layers-deep-learning-keras/
https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21
https://www.kaggle.com/thebrownviking20/intro-to-recurrent-neural-networks-lstm-gru

The Problem, Short-term Memory
Recurrent Neural Networks suffer from short-term memory. If a sequence is long enough, they’ll have a hard time carrying information from earlier time steps to later ones. So if you are trying to process a paragraph of text to do predictions, RNN’s may leave out important information from the beginning.
During back propagation, recurrent neural networks suffer from the vanishing gradient problem. Gradients are values used to update a neural network's weights. 
 
The vanishing gradient problem is when the gradient shrinks as it back propagates through time. If a gradient value becomes extremely small, it doesn’t contribute too much learning.

