# 🤖 Google | Kaggle AI Agent Workshop Repository

This repository hosts the materials, code, and resources from the **Google | Kaggle AI Agent Workshop**, a comprehensive 5-day program focused on the architecture, development, and deployment of modern AI agents.

## 🌟 Workshop Overview

This workshop covers the end-to-end lifecycle of AI Agent development, from foundational prompt engineering and architecture design to advanced topics like observability, inter-agent communication, and deployment strategies.

The primary resources are divided into daily modules, consisting of conceptual PDFs and hands-on, executable Jupyter Notebooks (`.ipynb`).

## 📁 Repository Structure

The files are organized to follow the workshop's daily progression:

| Directory/File | Type | Description |
| :--- | :--- | :--- |
| `day-1a-from-prompt-to-action.ipynb` | Code | Introduction to the Agent paradigm, prompt engineering, and the agentic loop. |
| `day-1b-agent-architectures.ipynb` | Code | Deep dive into various agent architectures (e.g., ReAct, Reflection). |
| `day-2a-agent-tools.ipynb` | Code | Implementing and utilizing external tools for agents. |
| `day-2b-agent-tools-best-practices.ipynb` | Code | Strategies and patterns for building robust and reliable tool usage. |
| `day-3a-agent-sessions.ipynb` | Code | Managing state and multi-turn conversations with agents. |
| `day-3b-agent-memory.ipynb` | Code | Implementing various memory mechanisms (short-term, long-term, RAG). |
| `day-4a-agent-observability.ipynb` | Code | Techniques and tools for monitoring and debugging agent behavior. |
| `day-4b-agent-evaluation.ipynb` | Code | Metrics and methods for testing and evaluating agent quality. |
| `day-5a-agent2agent-communication.ipynb` | Code | Building multi-agent systems and communication protocols. |
| `day-5b-agent-deployment.ipynb` | Code | Steps and considerations for deploying agents to production environments. |
| `Agent Quality.pdf` | PDF | Supplemental material on defining and measuring agent quality. |
| `Agent Tools & Interop...Protocol (MCP).pdf` | PDF | Documentation on tool interfacing and potentially the Multi-Agent Communication Protocol. |
| `Context Engineering_ Sessions & Memory.pdf` | PDF | Conceptual background for Day 3 topics. |
| `Prototype to Production.pdf` | PDF | A high-level guide covering the full development lifecycle. |

## 🛠 Prerequisites

To run the Jupyter Notebooks locally, you will need:

1.  **Python 3.x**
2.  **Jupyter** (Notebook or Lab)
3.  The specific dependencies used in the workshop (e.g., **LangChain, CrewAI, OpenAI/Google API client libraries**).

It is highly recommended to create a dedicated virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
