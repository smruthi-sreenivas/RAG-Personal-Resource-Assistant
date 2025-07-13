# RAG-Personal-Resource-Assistant

A Personal Resource Assistant that answers questions based on the content of your PDF documents. Using LangChain, Cohere, and ChromaDB, this system:

Ingests documents in PDF format

Extracts and stores document embeddings in a vector database for efficient retrieval

Allows users to input questions and receive answers from an LLM, based on relevant content from the documents

🔍 Features
✅ Upload and process personal documents (PDFs)

✅ Chunk and embed text using Cohere's embed-english-v3.0 model

✅ Store and retrieve embeddings using ChromaDB vector store

✅ Ask natural language questions and get contextual answers

✅ Built using LangChain’s Expression Language (LCEL)

🛠️ Tech Stack
LangChain – for chaining and prompt management

Cohere API – for embeddings and LLM responses (command-r model)

ChromaDB – for vector storage and similarity search

Python – core implementation

