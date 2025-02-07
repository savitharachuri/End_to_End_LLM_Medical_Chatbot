# End to End Medical Chatbot Generative AI


## Medical chatbot using OpenAI LLM model
### Project Description
A medical chatbot application by leveraging the Retrieval-Augmented Generation (RAG) process to fine-tune OpenAI's LLM responses for improved accuracy and relevance, with a user-friendly interface to facilitate seamless interaction.

### Methodology
- Knowledge Base Integration
The medical encyclopedia PDF serves as the external knowledge base for the chatbot. The document is parsed and preprocessed to extract relevant medical text for further processing.
- Vectorization and Embedding
The extracted text is converted into numerical vector representations using a word embedding model from Hugging Face. This ensures efficient retrieval and contextual understanding of medical information.
- Vector Storage and Retrieval
The generated vector embeddings are stored in Pinecone, utilizing AWS Free Tier for scalable and efficient vector-based search operations.
- LLM Integration
The stored vectors are retrieved and passed as input to OpenAI’s LLM API, enhancing response accuracy by incorporating relevant contextual information from the knowledge base.
- User Interface Development
A Flask-based web application is developed with HTML and CSS, providing an interactive and user-friendly interface for seamless chatbot interaction.

### Result

<img width="709" alt="Screenshot 2025-02-07 at 11 35 52 AM" src="https://github.com/user-attachments/assets/cdb5de93-5251-4184-9e39-809c7f4802d5" />

### Techstack Used:
- Python
- LangChain
- Flask
- GPT
- Pinecone
