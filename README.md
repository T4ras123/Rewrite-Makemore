# Implementation of makemore repo for learning purpoces

My implementation of [makemore](https://github.com/karpathy/makemore) ropository to learn LLMs

Already implemented:

- **Bigram** model with 1 charecter of context size and negative log-likelihood loss of ~2.7

- **Linear neural network model** with the same loss and result as a bigram, as the underlying processes are the same, but in the NN probabilities are learnt not counted

- **MLP** - multi-level preceptron with 27 x 10 embeding space and a context size of 6

- **ImageNet-like** model that helps with cramming data from n tokens of context to a one vector by grouping them first.

- **Small Transformer** - [SmallGPT](https://github.com/T4ras123/Small-GPT) "trained" on a tiny shakespeare dataset.
