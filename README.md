# Smart-Document-Querying-Leveraging-LlamaIndex-GradientAI-and-Cassandra
Deploy an advanced document querying system using open-source models and frameworks. This project integrates LlamaIndex for indexing, Cassandra for storage, and GradientAI for embeddings and LLMs. Demonstrates proficiency in leveraging open-source technologies, handling embeddings, and utilizing advanced querying techniques.
# Advanced Document Querying with Open-Source Models

## Overview

This repository showcases the integration of cutting-edge open-source models and frameworks to create an advanced document querying system. It uses LlamaIndex for indexing and querying, Cassandra for vector storage, and GradientAI for embeddings and LLMs. This project highlights expertise in leveraging open-source technologies, managing embeddings, and advanced querying techniques.

## Key Components

- **LlamaIndex:** Efficient document indexing and querying.
- **GradientAI:** Provides embeddings and LLMs for enhanced document understanding.
- **Cassandra:** Robust vector store for scalable storage and retrieval.
- **Open Source Models:** Utilizes Llama2-7b-chat for language modeling you can use any llm model and BGE-large for embeddings.
Environment Configuration:

Set GRADIENT_ACCESS_TOKEN and GRADIENT_WORKSPACE_ID as environment variables.
Ensure you have the secure connect bundle and token JSON file for Cassandra.
Run the Code:
Execute the script to connect to Cassandra, load documents, index them using LlamaIndex, and query for information.

## Code Highlights

**Cassandra Integration**: Connects to Cassandra using PlainTextAuthProvider and Cluster.
**LlamaIndex Usage**: Loads documents and creates a vector store index for efficient querying.
**GradientAI Models**: Utilizes GradientBaseModelLLM and GradientEmbedding for advanced NLP tasks.
**Document Querying**: Queries the indexed documents to retrieve relevant information.

## Technologies

**LlamaIndex**: For document indexing and querying.
**GradientAI**: For embeddings and LLMs.
**Cassandra**: For scalable vector storage.
**Open Source Models**: Leveraging Llama2 and BGE for NLP tasks.

## Example Usage

**Load Documents**: Place documents in the /content/Documents directory.
**Run Script**: Execute the script to index documents and perform queries.
**Query Results**: The script prints the response to a sample query.




