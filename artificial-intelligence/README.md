# Redis AI Capabilities

Redis AI Capabilities provide solutions for implementing artificial intelligence features in your applications. By leveraging Redis's high-performance data structures and search capabilities, you can build intelligent applications with memory, context awareness, and real-time processing.

## What are Redis AI Capabilities?

Redis AI Capabilities extend Redis with features specifically designed for AI applications. They allow you to:

- Store and retrieve vector embeddings for semantic search
- Implement short-term and long-term memory for AI agents
- Maintain context across multiple interactions
- Process and analyze data in real-time
- Build personalized and context-aware AI applications
- Implement efficient retrieval-augmented generation (RAG) systems

Redis AI Capabilities are fully integrated with Redis, providing high performance, scalability, and real-time processing with minimal latency.

## Applicability

Redis AI Capabilities are particularly useful for:

1. **Conversational AI agents**: Build chatbots and virtual assistants with memory and context awareness.
2. **Personalization systems**: Create personalized experiences based on user preferences and history.
3. **Retrieval-augmented generation**: Enhance large language models with relevant context from your data.
4. **Semantic search applications**: Implement natural language search using vector embeddings.
5. **Real-time AI processing**: Process and analyze data streams in real-time for AI applications.
6. **Multi-agent systems**: Build complex systems with multiple AI agents that can share information.
7. **Context-aware applications**: Maintain user context across multiple interactions and sessions.

## Use Cases

This module contains examples demonstrating different Redis AI capabilities:

| Use Case                           | Description                                                                                                 | Link                                                                 |
|------------------------------------|-------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| Agent Memory with Spring AI        | Demonstrates how to implement short-term and long-term memory for AI agents using Redis vector capabilities | [agent-memory-with-spring-ai](./agent-memory-with-spring-ai)         |
| RAG with Spring AI                 | Demonstrates how to implement Retrieval-Augmented Generation (RAG) using Spring AI and Redis Vector Store   | [rag-with-spring-ai](./rag-with-spring-ai)                           |
| Semantic Caching with Spring AI    | Demonstrates how to implement semantic caching to improve performance and reduce costs in LLM applications  | [semantic-caching-with-spring-ai](./semantic-caching-with-spring-ai) |
| Vector Search with Redis OM Spring | Shows how to implement vector similarity search (KNN) for semantic search applications with Redis OM Spring | [vector-search](../search/vector-search)                             |
| Vector Search with Spring AI       | Demonstrates integration of Redis Vector Search with Spring AI                                              | [vector-search-spring-ai](../search/vector-search-spring-ai)         |


Each submodule contains a complete Spring Boot application that demonstrates the respective Redis AI capabilities.
