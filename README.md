# Automatic Music Generation with Using Long Short Term Memory LSTM Model

The Long Short Term Memory Model, popularly known as LSTM, is a variant of Recurrent Neural Networks (RNNs) that can capture long term dependencies in the input sequence. LSTM has a wide variety of applications in Sequence to Sequence modeling tasks such as Speech Recognition, Text Summarization, Video Classification and so on.

![Generation](https://www.researchgate.net/profile/Lichao-Mou/publication/304029484/figure/fig4/AS:374461078491138@1466289886107/An-unrolled-recurrent-neural-network.png)

(An Unrolled Recurrent Neural Network)

The preparation of input and output sequences is similar to WaveNet. At each timestep, an amplitude value is fed into the Long Short Term Memory cell – it then computes the hidden vector and passes it on to the next timesteps.

The current hidden vector at timestep h_t is computed based on the current input a_t and previously hidden vector h_(t-1). This is how the sequential information is captured in any Recurrent Neural Network:

![Generation](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/12/lstm.jpg)

### Pros of LSTM:
* Captures the sequential information present in the input sequence

### Cons of LSTM:
* It consumes a lot of time for training since it processes the inputs sequentially


![Generation](https://www.researchgate.net/profile/Ke-Yan-4/publication/333791434/figure/fig1/AS:769860309090304@1560560409604/Unrolled-LSTM-uses-time-series-data-as-input.png)

