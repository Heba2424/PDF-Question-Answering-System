# PDF-Question-Answering-System

Developed an intelligent system using FAISS vector stores and generative models (GPT-2) for semantic search and text generation. The system extracts and processes text from PDFs, splits content into chunks, creates embeddings with SentenceTransformer, and enables interactive querying via Gradio.


this project aligns with the concept of Retrieval-Augmented Generation (RAG). In RAG, relevant documents or text chunks are retrieved (using something like FAISS) and then fed into a generative model (such as GPT-2) to generate a response based on the retrieved content.

In this project:

Retrieval: Use FAISS to search for relevant text chunks from the PDF based on the query.

Augmentation: These retrieved chunks are provided as context to the generative model (GPT-2).

Generation: GPT-2 then generates a response using the context from the retrieved chunks.
