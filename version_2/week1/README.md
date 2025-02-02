# Kickstarting a Data Flywheel

> This folder is meant to be a starting point Week 1 of [Systematically Improving RAG Applications](https://maven.com/applied-llms/rag-playbook).

A common question about RAG applications is how to evaluate them. Common advice is to launch to users, use an expensive method like Ragas to evaluate generations or hire human annotators out of the box.

This is expensive, time consuming and difficult to do well at the start. So what else can we do?

In this folder, we have the following notebooks:

1. `synthetic_questions.ipynb` - How can we use synthetic questions to get a sense of how well our retrieval system works?

2. `benchmark_retrieval.ipynb` - Now that we have some synthetic questions, how can use them effectively to compare different retrieval systems? What metrics should we be looking at?

3. `visualize_results.ipynb` - How can we use the results from our retrieval benchmarks and do some statistical testing to see if there are any significant differences between each retrieval method?

## Instructions

Before running the notebooks, you'll need to install the necessary dependencies. We've provided a `pyproject.toml` file to make this easier.

Please use a virtual environment to do so, we recommend using [uv](https://docs.astral.sh/uv/getting-started/installation/) to do so.

```bash
pip install -r pyproject.toml
```

This will install all the necessary dependencies for the project. Once you've done this, you can start running the notebooks.
