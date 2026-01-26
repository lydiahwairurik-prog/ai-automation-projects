# RAG Pipeline Workflows
Workflows related to RAG and chatbots

##Workflow: RAG Pipeline
**Description**
This workflow retrives a file from a folder in GOOGLE Drive, the file is downloaded then fed into a vector store.
##Chatbot
When a chat is started, the AI agent, uses its brain and information from the vector store to give an answer that best fits the question asked. 
**Nodes used**
-Google Drive trigger
-Googl Drive download file
-Simple Vector Store
-Embeddings Cohere
-Default Data Loader
-When chat message recievd trigger
-AI Agent
-Open Router
