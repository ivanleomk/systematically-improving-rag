# Overview

This folder contains the code for Week 2 of the Systematically Improving RAG course. In this portion, we'll talk briefly about fine-tuning embedding and cross encoder models.

## Instructions

This tutorial is split into 3 notebooks that build on each other:

1. **Synthetic Transactions**: Learn how to generate and iterate on synthetic data for fine-tuning
2. **Finetune Cohere**: Explore using Cohere's managed reranker service for quick wins
3. **Open Source Models**: Deep dive into fine-tuning open source embedding models

4. Create and activate a virtual environment

```
pip install -r pyproject.toml
```

2. Set up environment variables

```
export OPENAI_API_KEY=""
export WANDB_API_KEY=""
```

## Running the Notebooks

The notebooks should be run in order as they build upon each other:

### 1. Synthetic Transactions

This notebook covers:

- Generating synthetic transaction data
- Manual data labeling using Streamlit
- Initial evaluation using Braintrust

### 2. Finetune Cohere

This notebook covers:

- Preparing data for Cohere's reranker
- Fine-tuning a Cohere reranker model
- Evaluating reranker performance

### 3. Open Source Models

This notebook covers:

- Fine-tuning sentence transformers
- Hyperparameter optimization
- Model evaluation and comparison
