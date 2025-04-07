# Docker-Hosted-RAG-Deep-Learning-Example

A simple GenAI app for [Docker's Docs](https://docs.docker.com/) based on the [GenAI Stack](https://github.com/docker/genai-stack) PDF Reader application.

Allows LLM models to 'understand' external context (PDF docs in our case) without direct ML training.

Does this using vector embeddings to optimize similarity search between any query and external media to contextualize the correct semantics.

The LLM deciphers the semantics (since embedding to word goes both ways) with prompt engineering, then delivers a context-based response.

Docker makes the application portable, easy to deploy, and configure / customize.
