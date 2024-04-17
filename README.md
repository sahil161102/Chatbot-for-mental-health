# Mental Health chatbot with custom ChatGPT API
Description:
This repository contains the codebase and resources for a mental health-oriented chatbot developed using the ChatGPT API. The chatbot aims to provide support, information, and resources related to mental health queries. The project focuses on efficient communication, security, and accuracy.

Features:
* Adopts a prompt-based engineering method for quicker training and response time.
* Customized prompts guide the chatbot's interactions, a technique known as shot prompting.
* Refines prompts using the Langchain library, incorporating pre-trained language models.
* Optimized indexing and searching algorithms ensure faster and more accurate replies.
* Incorporates Pinecone Vector database for accurate data storage and retrieval.
* Performs precise Cosine similarity searches between user queries and stored documents.
* Uses OpenAI models: text-embedding-ada-002 for text-to-vector conversion, GPT Turbo 3.5 for natural conversations.



Query to LLM which acts as a friend or a mental health specialist based on input:
![openquery](/assets/open.png)

Vector results from pinecone DB which contains verified mental health resources.
![vector](/assets/vec.png)

References:

* https://docs.langchain.com/docs/
* https://platform.openai.com/docs/api-reference
* https://docs.streamlit.io/
* https://developers.google.com/maps/documentation
* https://docs.pinecone.io/docs/overview


