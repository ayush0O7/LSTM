## Projects Developed using LSTM in jupyter notebooks on kaggle.

**<h3>Project 1 : Sequence to sequence prediction</h3>** This project introduces the underlying principles of Long Short Term Memory (LSTM) networks through a straightforward sequence prediction task - forecasting the (n+1)th natural number based on a provided sequence of 'n' natural numbers.

The focal points of this project are:

* Gaining a solid understanding of the expected input shape for LSTM, which can take two forms - (batch_size, seq_len, feature_number) or (seq_len, batch_size, feature_number), and learning how to prepare the input data accordingly.
* Grasping the concept of 'hidden dimensions' in LSTM, which define the number of hidden states and impact the capacity and complexity of the model.
* Mastering the application of a fully connected layer to the output of the LSTM layer, to obtain predictions in the desired format and shape.

Through this project, the intention is to familiarize oneself with the basic building blocks of LSTM, setting a robust foundation for more complex applications in the future.


**<h3>Project 2 : Machine Translation(English to Hindi) </h3>** This project builds an end-to-end model for English to Hindi translation by closely implementing the key aspects of the  [paper](https://arxiv.org/abs/1409.3215).

I solved this problem in two parts.

Part 1 : Converting the sentences into sequences. This will include removing NaN values, basic pre-processing (removing punctuation, converting to lower-case), tokenization and vocabulary creation.

Part 2 : Building and training the seq2seq model, following the aforementioned paper closely. The seq2seq model feeds the input to an encoder, which adds embedding and feeds it to a multi-layered LSTM. The output cell and hidden states from the encoder are fed to the decoder which tries to predict a word of the target language at a time. 
