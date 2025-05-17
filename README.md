# Question Answering System using Simple RNN (PyTorch)

This repository contains a basic Question Answering (QA) system built using a Simple Recurrent Neural Network (RNN) in PyTorch. The system is designed to answer factual questions based on short context passages.

## 🧠 Model Architecture

- **Embedding Layer**: Converts input tokens into dense vectors.
- **Simple RNN Layer**: Processes sequential context and question tokens.
- **Linear Output Layer**: Maps RNN outputs to start and end positions of the answer span in the context.

## 📦 Features

- Trained on small-scale QA datasets like [SQuAD subset or toy data].
- Input: (context, question) pair
- Output: Predicted answer span from context
- Tokenization and padding handled via `torchtext` or custom tokenizer

