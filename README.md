1. Introduction :
   
This project implements a document-based intelligent chatbot using a technique known as Retrieval-Augmented Generation (RAG). At its core, the system integrates a Large Language Model (LLM) to provide human-like, context aware responses.
Unlike traditional chatbots that rely on predefined rules or generic web-trained models, this RAG-based approach enhances accuracy by retrieving relevant content from uploaded PDF documents before generating an answer. This makes it highly suitable for tasks involving domain-specific documents such as company policies, legal texts, or technical manuals.
The user interacts through a Streamlit web interface, where they can:
•	Upload one or more PDF documents.
•	Ask natural language questions.
•	Receive answers that are grounded in the exact content of those documents.

2. Tools and Platform Used :
   
• Programming Language: Python
• IDE: Visual Studio Code
• Web Framework: Streamlit
• LLM: langchain_google_genai
• Embedding & Retrieval: FAISS (Facebook AI Similarity Search)
• Text Processing: LangChain
• PDF Parsing: PyPDF2

3. Python Requirements :

To successfully run this project, you need to set up a Python environment with all required dependencies. Before installing the libraries, ensure you have created a .env file in your project directory to securely store your Google API key
Example = (GOOGLE_API_KEY=” your_google_api_key_here” )
Install the following Python packages:
• streamlit
• google-generativeai
• langchain
• PyPDF2
• chromadb
• faiss-cpu
• langchain_google_genai
• hnswlib
