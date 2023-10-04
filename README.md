# Deep-Learning-in-TensorFlow
Build predictive models using deep neural networks in TensorFlow, and apply them to a variety of real-world applications.

* Project: Predicting Listing Gains in the Indian IPO Market Using TensorFlow
* Sequence Models for Deep Learning
  * Introduction to RNNs
  * Basic RNN Architecture
  * Advanced RNN Architecture -- GRU and LSTM
    * Both models have their own unique internal mechanism for addressing the vanishing gradient problem (a common issue in traditional RNNs).
    
    **vanishing gradient problem : as networks become deeper, the influence of a given input on the hidden layers, and ultimately the output, tends to either decay to 0 or blow up exponentially as it cycles through the recurrence process. This problem compounds with longer sequences.
    
    RNNs :

    1. Long Short-Term Memory (LSTM) : incorporating a "memory cell" that can maintain information in memory for long periods of time, making them more suitable for tasks where the model needs to learn from context that spans many steps, such as language modeling and translation.
    <img width="522" alt="image" src="https://github.com/ChristineWeitw/Deep-Learning-in-TensorFlow/assets/58152741/00dd162e-2ea5-4496-969e-f80e8c392370">

    2. Gated Recurrent Units (GRUs) : include gates inside the nodes that determine what information to retain and what to forget.
    <img width="520" alt="image" src="https://github.com/ChristineWeitw/Deep-Learning-in-TensorFlow/assets/58152741/d55adecc-b88c-4b95-9388-1dd798a76f80">

    * Commonly used : LSTM > plain RNNs
    
    * Architecture simplicity : GRU > LSTM
  * Advanced RNN Architecture -- Convolutional Layers
  * Time Series Forecasting with RNNs
  * Guided Project: Time-Series Forecasting on the S&P 500
    - Our goal is to build a successful model to forecast how this index will move based on its past behavior.
* Natural Language Processing for Deep Learning
* Convolutional Neural Networks for Deep Learning
