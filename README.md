# Intelligent-Agent-Based-Book-Purchasing-System
This project demonstrates how a GPT-powered agent can autonomously negotiate and complete a book purchase using the OpenAI Assistants API. The system models a “Client Agent” that interacts with simulated bookstores, requests proposals, compares prices, and confirms the purchase — similar to behaviors found in JADE multi-agent systems.

🧠 Overview
- Client Agent: Uses OpenAI Assistants API to reason through function calls and agent communication steps.
- Bookstores (Simulated Sellers): Provide proposals in response to CFPs (Call For Proposals).
- Negotiation Logic: Agent evaluates multiple offers and accepts the most cost-effective one.
- Tool-Based Reasoning: Uses function calling for structured interaction between the agent and environment.

⚙️ Features
- Implements a JADE-like CFP negotiation protocol (Call for Proposal, Proposal, Acceptance).
- Uses OpenAI function calling for dynamic reasoning and decision-making.
- Simulates multi-agent communication with clear JSON-based interfaces.
- Demonstrates autonomous reasoning in practical procurement workflows.

🧩 Tech Stack
- Python
- OpenAI Assistants API (gpt-4o)
- json, time, os, google.colab.userdata


📚 Concept: This project explores intelligent negotiation systems powered by large language models.
It bridges classical agent theory (JADE) with modern LLM-based function calling, enabling fully autonomous purchasing decisions.
