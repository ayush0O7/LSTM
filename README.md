## Projects Developed primarily using LSTM in jupyter notebooks on kaggle.

**<h3>Project 1 : Simple Sequence to sequence prediction</h3>** This project introduces the underlying principles of Long Short Term Memory (LSTM) networks through a straightforward sequence prediction task - forecasting the (n+1)th natural number based on a provided sequence of 'n' natural numbers.

The focal points of this project are:

* Gaining a solid understanding of the expected input shape for LSTM, which can take two forms - (batch_size, seq_len, feature_number) or (seq_len, batch_size, feature_number), and learning how to prepare the input data accordingly.
* Grasping the concept of 'hidden dimensions' in LSTM, which define the number of hidden states and impact the capacity and complexity of the model.
* Mastering the application of a fully connected layer to the output of the LSTM layer, to obtain predictions in the desired format and shape.

Through this project, the intention is to familiarize oneself with the basic building blocks of LSTM, setting a robust foundation for more complex applications in the future.


**<h3>Project 2 : Machine Translation(English to Hindi)(In Progress)</h3>** This project intends to do English to Hindi translation by closely implementing the key aspects of the  [paper](https://arxiv.org/abs/1409.3215).

I am solving this problem in two parts.

Part 1[ DONE ] : Converting the sentences into sequences. This will include removing NaN values, basic pre-processing (removing punctuation, converting to lower-case), tokenization and vocabulary creation.

Part 2[In Progress] : Building and training the seq2seq model, following the paper closely.
