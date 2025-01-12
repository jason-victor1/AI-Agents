# Building Autonomous AI Agents With Python From Scratch

## Overview

This repository provides a comprehensive, step-by-step guide to building **Autonomous AI Agents** with Python. The project demonstrates how to create AI agents capable of performing specific tasks, integrating external tools, and making dynamic decisions. The implementations progress from basic examples to advanced, domain-specific agents.

Each agent leverages OpenAI's language models and Python-based frameworks to solve real-world problems. The repository also includes tools and guides, like **Basic Setup** and the **SimplerLLM Library**, which are critical for preparing the development environment and simplifying the process of creating AI agents.

---

## AI Agents Included in This Project

This project features multiple AI agents, each demonstrating different levels of complexity and automation. Below are the AI agent types included in this repository:

| **Agent Type**               | **Automation Level** | **Scope**                   | **Example Use Case**                              |
|-------------------------------|----------------------|-----------------------------|--------------------------------------------------|
| **[Hardcoded AI Agent](https://github.com/jason-victor1/Hardcoded-AI-Agent.git)** | Manual integration   | General-purpose           | Basic weather queries (manual function calls).   |
| **[ReAct Framework AI Agent](https://github.com/jason-victor1/ReAct-Framework-AI-Agent.git)** | Fully automated       | Dynamic decision-making   | Automated inquiries with external tool integration. |
| **[SEO Auditor AI Agent](https://github.com/jason-victor1/SEO-Auditor-AI-Agent.git)** | Fully automated       | Domain-specific (SEO)     | Analyze and optimize webpage performance.         |

These agents progress from a **Hardcoded AI Agent**, which introduces foundational concepts, to the advanced **SEO Auditor AI Agent**, which demonstrates domain-specific functionality.

---

## Tools for AI Agent Development

This repository includes two essential tools that simplify the development of AI agents. They are critical for setting up and managing the development environment.

### 1. [Basic Setup](https://github.com/jason-victor1/basic-setup.git)
- **Description:**  
  This guide provides the foundational setup for creating Python projects with OpenAI's API. It ensures your environment is configured correctly to start building AI agents.
- **Features:**  
  - Virtual environment setup.
  - Installation of necessary dependencies.
  - OpenAI API configuration.
- **Example Use Case:**  
  Set up your Python environment and authenticate with OpenAI for future AI agent projects.

---

### 2. [SimplerLLM Library](https://github.com/jason-victor1/SimplerLLM-library.git)
- **Description:**  
  A lightweight Python library designed to simplify interaction with language models like OpenAI’s GPT-4 or Anthropic’s Claude. It is used extensively across AI agent projects to streamline development workflows.
- **Features:**  
  - Simplifies interaction with AI language models.
  - Includes built-in tools for data extraction and API integration.
  - Reduces boilerplate code, allowing developers to focus on agent logic.
- **Example Use Case:**  
  Use SimplerLLM to replace complex setup and dependencies for a more efficient development process.

---

## Agent Descriptions

### 1. [Hardcoded AI Agent](https://github.com/jason-victor1/Hardcoded-AI-Agent.git)
- **Description:**  
  A basic example of an AI agent with predefined functionality to introduce core concepts.
- **Features:**  
  - Uses static functions and hardcoded logic to generate responses.
  - Demonstrates how to manually integrate external tools.
- **Example Use Case:**  
  *"Should I take an umbrella in California?"*  
  - A hardcoded weather function provides the response.

---

### 2. [ReAct Framework AI Agent](https://github.com/jason-victor1/ReAct-Framework-AI-Agent.git)
- **Description:**  
  A more advanced AI agent that utilizes the **ReAct Framework** for dynamic execution of actions.
- **Features:**  
  - Implements a "Thought → Action → Action Response" loop.
  - Dynamically selects and executes appropriate functions based on the user query.
  - Capable of integrating external tools for enhanced functionality.
- **Example Use Case:**  
  *"What’s the weather in New York?"*  
  - The agent calls a weather API and provides the response dynamically.

---

### 3. [SEO Auditor AI Agent](https://github.com/jason-victor1/SEO-Auditor-AI-Agent.git)
- **Description:**  
  A domain-specific AI agent for SEO analysis and webpage performance optimization.
- **Features:**  
  - Integrates external APIs to fetch SEO data (e.g., image counts, keyword analysis, response times).
  - Provides actionable recommendations for webpage optimization.
- **Example Use Case:**  
  *"How many images are on the webpage example.com?"*  
  - The agent fetches and analyzes SEO data using an external API and generates insights.

---

## Key Takeaways

- **Automation Levels:** The repository demonstrates progression from manual integration (Hardcoded Agent) to fully automated agents (ReAct Framework and SEO Auditor AI Agent).
- **Practical Use Cases:** Each agent serves a unique purpose, from basic queries to solving real-world problems like SEO analysis.
- **Development Tools:** The **Basic Setup** and **SimplerLLM Library** simplify environment setup and streamline workflows.
- **Dynamic Decision-Making:** The ReAct framework enables agents to analyze tasks, select tools, and seamlessly integrate results.

---

## Future Work

- Expand functionality to include additional domain-specific agents, such as:
  - Financial analysis agents.
  - Medical diagnostics agents.
- Optimize existing agents for enhanced performance and multi-functionality.
- Explore integrating additional APIs for broader capabilities.
- Build frontend interfaces for user-friendly interaction.

---

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/jason-victor1/AI-Agents.git
   cd AI-Agents
   ```

2. Follow the instructions in the **Basic Setup** repo to configure your development environment.

3. Use the **SimplerLLM Library** for efficient AI agent creation.

4. Explore and build the included AI agents, starting with the **Hardcoded AI Agent** and progressing to the **SEO Auditor AI Agent**.
