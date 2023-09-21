# Deep-Learning-in-TensorFlow
Build predictive models using deep neural networks in TensorFlow, and apply them to a variety of real-world applications.

* Project: Predicting Listing Gains in the Indian IPO Market Using TensorFlow
* Sequence Models for Deep Learning
  * Introduction to RNNs
  * Basic RNN Architecture
  * Advanced RNN Architecture -- GRU and LSTM
    
        * Both models have their own unique internal mechanism for addressing the vanishing gradient problem (a common issue in traditional RNNs).
    
        * **vanishing gradient problem : as networks become deeper, the influence of a given input on the hidden layers, and ultimately the output, tends to either decay to 0 or blow up exponentially as it cycles through the recurrence process. This problem compounds with longer sequences.
    
    RNNs :

           1. Long Short-Term Memory (LSTM) : incorporating a "memory cell" that can maintain information in memory for long periods of time, making them more suitable for tasks where the model needs to learn from context that spans many steps, such as language modeling and translation.
    
           2. Gated Recurrent Units (GRUs) : include gates inside the nodes that determine what information to retain and what to forget.
    
        * Commonly used : LSTM > plain RNNs
    
        * Architecture simplicity : GRU > LSTM
  * Advanced RNN Architecture -- Convolutional Layers
  * Time Series Forecasting with RNNs
  * 
* Natural Language Processing for Deep Learning
* Convolutional Neural Networks for Deep Learning
