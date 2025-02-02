# README

This folder contains the code for the final week of the Systematically Improving RAG course. In this week, we'll be looking into how to improve the tool calling capabilities of our application.

Specifically, we'll do so by looking at a simple case study of Raycast's extensions and how they're hoping to support natural language queries to trigger shortcuts.

We'll do so using the following notebooks

1. **1. Evaluate Tools.ipynb** : We'll first look at how we can use simple metrics like precision and recall to evaluate tool calling capabilities of our application. We'll also examine some simple ways that we can segment our results to get a better understanding of how our model might be struggling with specific tools or combinations of tools.

2. **2. Create Dataset.ipynb** : We'll then look at how we can create a synthetic dataset of queries that we can use to evaluate the tool calling capabilities of our application. We'll do so by looking at a small subset of Raycast's extensions and generating queries that we hope to trigger these extensions.

3. **3. Improve Capabilities.ipynb** : Finally, we'll look at how we can improve the tool calling capabilities of our application. We'll do so by looking at some of the most common techniques used to improve tool calling capabilities, such as few shot examples and how we can scale up the number of tools we're using using dynamic retrieval.
