This repository contains a modular Retrieval-Augmented Generation (RAG) system designed to query custom document datasets using multiple state-of-the-art Large Language Models. By unifying OpenAI (GPT), Groq (Llama/Mixtral), and Anthropic (Claude) APIs into a single pipeline, this project allows developers to benchmark performance, leverage high-speed inference, and generate highly grounded responses.

Features
Multi-LLM Integration: Seamlessly toggle between OpenAI models, Anthropic's Claude family, and Groq's high-speed inference endpoints.

Modular Retrieval: Built on LangChain to easily swap out vector stores, embeddings, and prompt templates.

Fallback Mechanisms: Route queries to alternative models if specific endpoints (like deprecated Groq models) face rate limits or context overflow.

Experimentation Ready: Structured for rapid testing and prototyping directly within Jupyter Notebooks.

Tech Stack
Language: Python

Framework: LangChain

APIs: langchain-openai, langchain-groq, langchain-anthropic

