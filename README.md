# Transformer

English-to-Italian Translation with Transformer Model
This repository contains a sequence-to-sequence Transformer model, built from scratch, designed to translate text from English to Italian. The model is based on the architecture described in the paper "Attention Is All You Need" and implemented using TensorFlow and Keras.

## Project Overview

The main goal of this project is to develop a lightweight yet efficient translation model capable of performing English-to-Italian translations. Despite the relatively small size of the model, it achieves impressive translation quality, as demonstrated by the ROUGE scores.  

## Characteristics of a transformer 

Positional encoding: Instead of looking at each word in the order that it appears in a sentence, a unique number is assigned to each word. This provides information about the position of each token (parts of the input such as words or subword pieces in NLP) in the sequence, allowing the model to consider the sequence's sequential information.

Attention: Attention is a mechanism that calculates weights for every word in a sentence as they relate to every other word in the sentence, so the model can predict words which are likely to be used in sequence. This understanding is learned over time as a model is trained on lots of data. The self-attention mechanism allows each word to attend to every other word in the sequence in parallel, weighing their importance for the current token. In this way, it can be said that machine learning models can “learn” the rules of grammar, based on statistical probabilities of how words are typically used in language.

