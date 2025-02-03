# Local RAG




## Simple implementations of RAGs
Retrieval-Augmented Generation (RAG) were introduced 2021 in [here](https://arxiv.org/abs/2005.11401).
Very simply put, RAGs combine pretrained Large Language Models (LLMs) with local databases.
The idea behind this approach is to leverage the power and vast text understanding power of the pretrained models, and add up-to-date, private and/or very specific knowledge database to it.
For example, the following code will use PDF from research papers as database, so that the LLM can answer specific questions that can only be answered by someone who has an understanding of the underlying papers.
Furthermore, almost all well established pretrained LLM models occupie a lot of memory, are compute intensive and are not freely available. 
Therefore, the following code provides an adaptations of the publicly available Langchain notebooks [here](https://github.com/langchain-ai/rag-from-scratch/tree/main) to make it possible to run the RAGs localy with open-source models.

# Prerequisite
- anaconda3
- Ollama
- langchain
- langchain_ollama
- (Please be aware the prerequisites may not be complete and errors may appear for missing packages or libraries.)
