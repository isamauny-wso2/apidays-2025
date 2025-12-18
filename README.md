# APIDays 2025 / FOST - Conference Materials

This repository contains presentation materials and supporting resources for API Days 2025 conference sessions focusing on AI integration with APIs and API governance.

## Contents

### Presentations

#### API-AI: Lessons From the Trenches
Explores practical lessons learned from implementing AI capabilities with APIs in production environments.

- [API-AI-LessonsFromtheTrenches.pdf](API-AI-LessonsFromtheTrenches.pdf) - Complete presentation

#### Governance-API-MCP
Covers API governance strategies and the Model Context Protocol (MCP) for building AI agents that interact with APIs.

- [Governance-API-MCP.pdf](Governance-API-MCP.pdf) - Complete presentation

### Supporting Materials

#### Diagrams

- [Deployment.jpg](Deployment.jpg) - Deployment architecture diagram
- [agent-llm-diagram.txt](agent-llm-diagram.txt) - Sequence diagram showing Agent-LLM-MCP execution flow

## Key Topics

- **AI Integration with APIs**: Best practices and lessons learned from real-world implementations
- **Model Context Protocol (MCP)**: Framework for building AI agents that can interact with external tools and APIs
- **API Governance**: Strategies for managing and governing APIs at scale
- **Agent Architecture**: How LLMs, agents, and MCP servers work together to process user requests

## Example Flow

The repository includes a detailed sequence diagram demonstrating how an AI agent processes a natural language query ("Will I need an umbrella in Paris tomorrow?") by:

1. Receiving user input
2. Using an LLM to determine which tools to call
3. Invoking a Weather MCP Server to fetch real-time data
4. Processing the results through the LLM
5. Returning a natural language response to the user

## Conference

**API Days 2025**
Presentations delivered December 2025

## License

Conference materials - All rights reserved.

## Author

Isabelle Mauny
