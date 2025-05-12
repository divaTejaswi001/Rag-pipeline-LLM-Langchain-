# Rag_pipeline-LLM-Langchain-
An end-to-end Retrieval-Augmented Generation (RAG) pipeline using LangChain, Qdrant, Sentence Transformers, and LLaMA 3.2. This app allows you to upload any PDF, convert its content into vector embeddings, store them in a local Qdrant database, and ask context-aware questions powered by LLMs — all with a simple Gradio interface.

1.  Install Required Libraries:

'''pip install -r requirements.txt'''

2. Start the Qdrant Vector Database:
Make sure Docker is installed, then run:

'''docker run -p 6333:6333 -p 6444:6444 qdrant/qdrant'''

4. Run Ollama with LLaMA 3.2:
   
'''ollama run llama3:2'''

5. Run all the cells

Can use the sample india.pdf to upload

Gradio UI

![Screenshot 1](https://github.com/user-attachments/assets/2e091660-dc2c-4f47-82f3-82676c8d90ad)
![Screenshot 2](https://github.com/user-attachments/assets/d80da51f-9fa2-4c8a-be06-e9af5f1cb99a)
![Screenshot 3](https://github.com/user-attachments/assets/352b1c91-6b90-4d8a-9531-79227044990a)
![Screenshot 4](https://github.com/user-attachments/assets/77e6fa3e-df85-4e7f-9139-638bd8738a60)
