# Local RAG




## Simple implementations of RAGs
Retrieval-Augmented Generation (RAG) was introduced in 2021 in [here](https://arxiv.org/abs/2005.11401).
Very simply put, RAGs combine pre-trained Large Language Models (LLMs) with local databases.
The idea behind this approach is to leverage the power and vast text understanding power of the pre-trained models and add an up-to-date, private, and/or very specific knowledge database to it.
For example, the following code will use PDFs from research papers as a database so that the LLM can answer specific questions that can only be answered by someone who has an understanding of the underlying papers.
Furthermore, almost all well-established pre-trained LLM models occupy a lot of memory, are compute-intensive, and are not freely available. 
Therefore, the following code provides an adaptation of the publicly available Langchain notebooks [here](https://github.com/langchain-ai/rag-from-scratch/tree/main) to make it possible to run the RAGs locally with open-source models and use a local folder with PDFs as database.

# Prerequisite
- anaconda3
- Ollama
- langchain
- langchain_ollama
- (Please be aware the prerequisites may not be complete, and errors may appear for missing packages or libraries. In that case, just install the missing libraries.)

# Provided Implementations
- Basic_RAG.ipynb: Straightforward implementation of a locally run RAG
- Rag_Fusion.ipynb: Implementation of the RAG Fusion approach from [Z. Rackauckas](https://arxiv.org/abs/2402.03367)
- MultiQuery.ipynb: Implementation of the Multi Query approach, to be found in the Langchain repository [Part 5](https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_5_to_9.ipynb)

  
