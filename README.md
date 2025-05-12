# Rag_pipeline-LLM-Langchain-
An end-to-end Retrieval-Augmented Generation (RAG) pipeline using LangChain, Qdrant, Sentence Transformers, and LLaMA 3.2. This app allows you to upload any PDF, convert its content into vector embeddings, store them in a local Qdrant database, and ask context-aware questions powered by LLMs — all with a simple Gradio interface.

1.  Install Required Libraries:

pip install -r requirements.txt

2. Start the Qdrant Vector Database:
Make sure Docker is installed, then run:

docker run -p 6333:6333 -p 6444:6444 qdrant/qdrant

4. Run Ollama with LLaMA 3.2:
   
ollama run llama3:2

5. Run all the cells

Can use the sample india.pdf to upload
