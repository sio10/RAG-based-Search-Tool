# RAG-based-Search-Tool
Retrieval-Augmented Generation (RAG) Based Search Tool, to search through documents quickly and efficiently.

# Requirements
Requires Llama 2 access from HuggingFace hub.
  -  Apply first on LLama 2 website
  -  Then apply on HuggingFace and obtain token

# How to run 
Use Google Colab on GPU runtime (T4 minimum) to run the code

# LLM used - Llama 2 & Framework - Llama Index
Taking Llama 2 as the querying LLM and sentence-transformers as the vector embedding model the model creates a vector store of input documets and then allows querying on the those documents to efficienlty and quickly obtain information from the corpus

Llama Index for the framwork to be able to locally store and work on the Vecor store and the llm models involved.
Alternate options for vector store include - Qdrant & Pinecone 
