# Transformer based Machine Translation Model from Scratch
# "ATTENTION IS ALL YOU NEED"
This research paper "Attention is all you need" by Vaswani et al (https://arxiv.org/pdf/1706.03762) sparked my deep fascination with Natural Language Processing and ignited my journey into this field. As a tribute I am trying to implement the whole model from scratch.  

This repository contains a custom implementation of a Transformer model built from scratch using PyTorch. I have used this model for Machine Translation (English-to-German), using the WMT14 dataset. The project includes training a Transformer model from scratch, fine-tuning, and generating translations for English sentences into German. You can use it for various tasks like Machine Translation, Text classification, Text generization and summarization, etc.

Project Overview
This project implements a Transformer model for the task of machine translation using PyTorch. It utilizes the WMT14 English-German dataset and a custom Transformer architecture to translate English sentences into German.

Key Features:
 - Custom Transformer Model: Implements a multi-head attention mechanism, positional encoding, and encoder-decoder structure from scratch.
 - Dataset: Uses the WMT14 dataset for training.
 - Training: The model is trained using a subset of the dataset (5%) to manage computational resources and time.
 - Translation: After training, the model can be used to translate English sentences to German.
 - Tokenization: Uses AutoTokenizer from Hugging Face's Transformers library for tokenizing both English and German sentences.

## Note
Due to the extensive time required for training (with one epoch estimated to take approximately 129 hours), I am currently unable to complete the full training process. However, I have provided the complete code in this repository, which can be used to train the model further. I encourage anyone interested to run the training or fine-tune the model based on their available resources.
