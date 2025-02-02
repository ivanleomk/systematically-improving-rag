# Systematically Improving Your RAG

In this week's notebooks, we'll be working on improving the retrieval of our RAG system when we deal with multimodal data. To do so, we'll leverage LLM generated metadata to improve the retrieval of our RAG system.

We'll do so in three notebooks

1. `1. Generate Dataset.ipynb`: We'll first use the `irow/ClothingControlV2` dataset to generate a new dataset for our case study.
2. `2. Structured Extraction.ipynb`: We'll then perform structured extraction on the generated dataset to add more metadata to the items. Specifically, we'll add a `material`, `occasion`, `style` filter to the items which will allow us to improve the retrieval of our RAG system.
3. `Text-2-SQL.ipynb` : Lastly, we'll generate some random SKU data for the items in the Clothing Control dataset to simulate an actual e-commerce dataset. We'll then perform some simple Text-2-SQL to retrieve the most relevant items for a given query.

We'll be using a set of defined categories that we've generated for the `irow/ClothingControlV2` dataset defined in the `categories.yml` file.
