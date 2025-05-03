# documents-rag
Langflow code to implement RAG (Retrieval Augmented Generation)  application

## Platform
- DataStax Langflow
- Serverless Vector DB - DataStax Astra DB
- LLM - Anthropic Sonnet 3.7
- Embeddings - Astra Vectorize (in-built)

## Prerequisites
- Langflow - Used Managed platform from DataStax for this example
- Vector DB - Used from DataStax for this example
- LLM Keys - used Anthropic API key, may be updated to use others

## How to use
1. Import the JSON file, document-rag.json into Langflow
2. Update the following variables with appropriate values
  * ANTHROPIC_API_KEY
  * ASTRA_DB_APPLICATION_TOKEN
  * ASTRA_DB_API_ENDPOINT
3. Use Langflow Playground to load a document and test
4. Publish and use
