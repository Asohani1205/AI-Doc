## Medical Text Retrieval and Answering System
This repository contains the code for a language model-based system designed to efficiently retrieve and answer queries from medical texts. The system utilizes LangChain for structured querying and Pinecone for efficient vector storage and retrieval.
## Features
Features
PDF Extraction: Extracts text data from PDF documents to process medical literature.
Text Splitting: Splits extracted text into manageable chunks for better handling and embedding.
Embedding Generation: Uses Hugging Face's sentence transformers to generate embeddings of the text chunks.
Pinecone Integration: Manages and retrieves text chunk embeddings using Pinecone, a vector database suited for similarity search.
Query Answering: Utilizes a language model to answer queries based on the most relevant text chunks retrieved from Pinecone.
## Installation
Before running the project, ensure that you have Python installed on your machine. Then, install the required packages using the following command:
## Documentation
For more details on the methods and classes used, refer to the LangChain documentation and the Pinecone documentation.

## Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.
