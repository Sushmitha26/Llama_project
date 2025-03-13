# Llama_project

A RAG based project to implement search on pdfs, using Llama 2, Llama Index and Huggingface.
Llama 2 : large language model to generate answers based on retrieved PDF content
Llama Index: Framework that helps in chunking, indexing and querying documents using embeddings and vector stores, it organizes and retrieves data efficiently for LLMs.
HuggingFace: Platform that helps users build, train, and deploy machine learning (ML) models. It allows users to share and browse pre-trained embedding models, finetune them and host.

## Workflow
1️⃣ PDFs are processed and indexed using LlamaIndex.  
2️⃣ Hugging Face embedding model allow for efficient search by turning text into vectors.  
3️⃣ A user query is matched to relevant document sections via embeddings.  
4️⃣ The retrieved text is passed to Llama 2, which generates a final answer.
