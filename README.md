**Overview**
The Research Paper Intelligence Assistant is an AI-powered application that answers questions about a research paper. It uses Retrieval-Augmented Generation (RAG) to retrieve relevant passages from the paper and generate answers using a language model.

**Features**
- Extracts text from research paper PDFs.
- Splits text into smaller chunks for efficient retrieval.
- Generates semantic embeddings using Sentence Transformers.
- Uses FAISS for similarity-based passage retrieval.
- Uses Qwen2.5-1.5B-Instruct to generate answers.
- Provides an interactive question-answering interface using Gradio.
- Displays retrieved source passages to help users verify answers.

**Technologies Used**
- Python
- Google Colab
- PyMuPDF
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- Qwen2.5-1.5B-Instruct
- Gradio

**HOW IT WORKS**
1. Extract text from a research paper PDF.
2. Split the text into overlapping chunks.
3. Convert the chunks into vector embeddings.
4. Store the embeddings in a FAISS index.
5. Convert a user's question into an embedding.
6. Retrieve the most relevant passages.
7. Provide the passages and question to the language model.
8. Display the generated answer and retrieved sources through Gradio.

**OBJECTIVE**
The goal is to make research papers easier to explore by allowing users to ask questions in natural language rather than manually searching through long documents.


