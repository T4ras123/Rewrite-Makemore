# Makemore Implementation for Learning Purposes

This repository contains my implementation of the [makemore](https://github.com/karpathy/makemore) project by Andrej Karpathy. The goal of this project is to learn about language models (LLMs) through hands-on coding and experimentation.

## Implemented Models

### Bigram Model

- **Description**: A simple bigram model with a context size of 1 character.
- **Loss**: Achieves a negative log-likelihood loss of approximately 2.7.

### Linear Neural Network Model

- **Description**: A linear neural network model that mirrors the bigram model in terms of loss and results. The probabilities are learned rather than counted.
- **Loss**: Similar to the bigram model, with a negative log-likelihood loss of approximately 2.7.

### Multi-Layer Perceptron (MLP)

- **Description**: An MLP with a 27 x 10 embedding space and a context size of 6 characters.
- **Loss**: Improved performance over the bigram and linear models.

## Notebooks

- [Bigram.ipynb](Bigram.ipynb): Implementation and experimentation with the bigram model.
- [Linear-NN.ipynb](Linear-NN.ipynb): Implementation of the linear neural network model.
- [MLP_manual_backprop.ipynb](MLP_manual_backprop.ipynb): Manual backpropagation implementation for the MLP.
- [MLP.ipynb](MLP.ipynb): Standard implementation of the MLP.
- [understand-statistics-in-BatchNorm.ipynb](understand-statistics-in-BatchNorm.ipynb): Understanding the statistics involved in Batch Normalization.
- [WaveNet-for-language-processing.ipynb](WaveNet-for-language-processing.ipynb): Implementation of a WaveNet model for language processing.

## Data

- [names.txt](names.txt): Dataset used for training and evaluation.

## Getting Started

To get started with this project, clone the repository and open the Jupyter notebooks in your preferred environment. Each notebook contains detailed explanations and code for the respective models.

```sh
git clone https://github.com/yourusername/makemore-implementation.git
cd makemore-implementation
```
