# MCP from Scratch

## Overview

The `mcp.ipynb` file is a core component of this project. It demonstrates the process of working with documents, including loading, processing, and creating a vector store for further use in machine learning or natural language processing tasks.

## Key Steps in `mcp.ipynb`

1. **Loading Documents**:
   - The `load_langgraph_docs()` function is used to load documents and calculate tokens per document.

2. **Saving Documents**:
   - The `save_llms_full(documents)` function saves the loaded documents to a file for persistence.

3. **Splitting Documents**:
   - The `split_documents(documents)` function splits the documents into smaller chunks for easier processing.

4. **Creating a Vector Store**:
   - The `create_vectorstore(split_docs)` function creates a vector store from the split documents, which can be used for tasks like similarity search or embedding-based queries.

## Dependencies

Ensure the following dependencies are installed:
- Python 3.x
- Required libraries (e.g., OpenAI, LangChain, or any other libraries used in the project)

## Environment Setup

The project may require an OpenAI API key for certain operations. Ensure the API key is set up as an environment variable (`OPENAI_API_KEY`) or loaded through a configuration file.

## Usage

1. Open the `mcp.ipynb` file in Jupyter Notebook or VS Code.
2. Run the cells sequentially to execute the document processing pipeline.
3. Use the generated vector store for downstream tasks.

## Notes

- The implementation of the functions (`load_langgraph_docs`, `save_llms_full`, `split_documents`, and `create_vectorstore`) is modular, making it easy to adapt or extend for other use cases.
- Ensure proper handling of sensitive information like API keys.
