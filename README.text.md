# Language Modeling - Text Generation with Markov Chain and LSTM

This work is about generating text by training language models based on Markov Chain and Recurrent Neural Networks (especially LSTM - Long Short Term Memory). Then we evaluate their effectiveness.

## Problem formulation

The goal of a language model is to probabilty of appearing a text.

- Chain rule:
$$p(w) = p(w_1) * p(w_2) * p(w_3) * ... * p(w_k)$$

- Markov assumption:
$$p(w) = p(w_1|start) * p(w_2|w_1) * p(w_3|w_2) * ... * p(w_k|w_{k-1})$$


## Markov Language Model

## LSTM Model
