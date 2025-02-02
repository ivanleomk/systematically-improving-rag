# Introduction

In this project, we'll look at how we can use topic modelling as a way to start classifying queries into different underlying categories. We'll be using a synthetic dataset of user queries generated from the Klarna FAQ to show how we can use topic modelling to break down our queries into different segments.

The notebooks in this project should be run in the following order:

1. `1. Generate Dataset.ipynb`: Generates a synthetic dataset of user queries with underlying labels. We've provided a complete dataset in the repo but you can also take a stab at generating your own if you'd like to with new categories.
2. `2. Cluster.ipynb`: We'll then show how we can use clustering to identify groups of queries that are similar to each other.
3. `3. Classifier.ipynb`: Finally, we'll use BERTopic to train a topic model, see what topics might emerge from these user queries and then see how closely these topics aligned with our original labels.

## Installation Instructions

1. To start, first install all the required dependencies

```bash
uv pip install -r pyproject.toml
```

If you're facing an issue with the installation of BERTopic on mac as seen below

```
RuntimeError: Could not find a `llvm-config` binary. There are a number of reasons this could occur, please see: https://llvmlite.readthedocs.io/en/latest/admin-guide/install.html#using-pip for help.
```

You'll need to install llvm using homebrew

```bash
brew install llvm
```

2. Then make sure that you point the environment variable `LLVM_CONFIG` to the llvm installation path. You can do this by running

```bash
which llvm-config
#> This gives an output
```

```bash
export LLVM_CONFIG=/opt/homebrew/opt/llvm/bin/llvm-config
```
