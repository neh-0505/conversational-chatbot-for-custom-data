Building a RAG System and Conversational Chatbot with Custom Data
This project demonstrates the implementation of a Retrieval-Augmented Generation (RAG) system integrated with a conversational chatbot, designed to handle custom datasets. RAG combines a retrieval-based approach, using pre-trained language models to fetch relevant documents, with a generation-based system that crafts natural responses using the retrieved information.

The system is built with the following key components:

Retriever: Uses a dense retriever (such as DPR) to fetch relevant context from a custom dataset.
Generator: Employs a transformer-based language model to generate responses based on retrieved documents.
Pipeline: The retrieval and generation steps are combined into a seamless pipeline, enabling the chatbot to produce informative and accurate answers grounded in external data sources.
This approach enhances the chatbot's ability to provide factually grounded responses, making it suitable for applications requiring reliable and dynamic knowledge bases. The implementation demonstrates how to fine-tune the retriever and generator on custom data, enabling efficient handling of domain-specific queries.

DEMO:
[Video 9-22 at 14.02.webm](https://github.com/user-attachments/assets/59c678ea-b336-4925-993d-5e011bbaa2a7)

IMPROVEMENTS:
this chatbot can be further improved by using advanced LLM models and advanced computing resources like and GPU and TPU for quicker response

Run below command to use the chatbot:

