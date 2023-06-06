# Q-A-with-Langchain-and-GPT3
The goal of this project is to build a proof of concept Q&amp;A web app that takes product documentation by ulr, Discord chat messages, support tickets (Zendesk) and Gmail emails as a knowledge base and provides relevant answers to user questions.

Problem Description
The goal of this project is to build a proof of concept Q&A web app that takes product documentation by ulr, Discord chat messages, support tickets (Zendesk) and Gmail emails as a knowledge base and provides relevant answers to user questions.

Acceptance Criteria
The app must be able to accurately answer user questions based on the knowledge base of product documentation, Discord chat messages, and Gmail emails.

The app must have a simple and user-friendly UI that allows users to input docs URLs, connect Discord, connect Zendesk, connect Gmail, and ask questions and receive relevant answers. The UI design part is on me.

The app must be able to scrape docs webpages, clean and preprocess the data, and convert it into numerical vectors for analysis. Our docs are hosted in the Zendesk Guide. For scrapping the docs, you can try this https://llamahub.ai/l/web-knowledge_base

*The user must be able to authorize access to Zendesk, Gmail and Discord. Open source connector hub solutions like Airbyte or Meltano can be helpful here. The app must process and prepare the data for LLM.

The app must have a vector database that enables fast and efficient retrieval of the most relevant vectors.

The app must be able to integrate with GPT3 to generate relevant and accurate answers to user questions.

The app must have short-term and long-term memory capabilities to improve the accuracy and relevance of the answers over time.

The app must provide a source attribution to help users verify the accuracy of the information.

The app must be scalable and optimized for performance.

The app must be secure and protect user data.

The app must be well-documented and have unit tests to ensure code quality and maintainability.

Technical Details
Langchain, Pinecone or Weaviate or other vector db solutions. This is TBD.

