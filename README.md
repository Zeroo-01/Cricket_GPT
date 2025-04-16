# Cricket Chatbot with LangChain and FastAPI

This project demonstrates how to build a cricket-themed chatbot using LangChain for natural language understanding and FastAPI for creating a web API. The chatbot can answer questions related to cricket by processing and analyzing documents from Wikipedia, generating embeddings, and utilizing NVIDIA AI models for generating responses.


![Cricket Chatbot UI](https://github.com/user-attachments/assets/1c3b527c-755f-4c36-9730-729ba51dbcc3 "Cricket Chatbot User Interface")




## Features

-   Employs Retrieval-Augmented Generation (RAG) to combine the strengths of retrieval and generative models, enhancing the accuracy of chatbot responses.
-   Utilizes LangChain, a comprehensive framework designed to simplify the development of advanced natural language processing models like RAG.
-   Processes and analyzes cricket-related documents sourced from Wikipedia, providing a rich knowledge base for the chatbot.
-   Creates document chunks and leverages vector embeddings for efficient information retrieval, enabling the chatbot to access relevant content quickly.
-   Implements a self-querying retriever mechanism within LangChain, allowing the chatbot to dynamically query its knowledge base based on user inputs.
-   Integrates chat memory to maintain context across interactions, improving the coherence and relevance of responses over time.
-   Configures the chatbot to generate human-like responses using NVIDIA NIM Inference models, ensuring answers are both informative and engaging.
-   Provides a RESTful API using FastAPI, facilitating easy integration of the chatbot into various applications and platforms.
-   Offers a comprehensive guide within a Jupyter Notebook environment, making it accessible for users to follow along and build their own cricket chatbot.
- A user-friendly ReactJS frontend to facilitate intuitive interaction with the cricket chatbot, offering a seamless user experience.


## Requirements

- Python 3.7+

- FastAPI

- Uvicorn (for running the FastAPI app)

- LangChain (and its dependencies)

- NVIDIA AI model access (requires API keys)
