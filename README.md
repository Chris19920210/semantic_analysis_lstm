# semantic_analysis_lstm
This is the tensorflow version for the theano demo:
http://deeplearning.net/tutorial/lstm.html

Some modifications are made:

The modified LSTM cell in the theano code (for parallel convenience) is substituted by GRU cell (reducing the computation complexity). Furthermore, dynamic_rnn is taken in this case for fully unrolling the GRU layer. 
