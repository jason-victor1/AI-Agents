# Building Autonomous AI Agents With Python From Scratch

## Overview

This repo provides a step-by-step guide to building **Autonomous AI Agents** with Python. I learned how to create AI agents capable of performing specific tasks, integrating external tools, and making dynamic decisions. This project demonstrates progressively advanced implementations. It starts with a basic agent and culminating in a domain-specific agent.

The agents are designed using OpenAI's language models and Python-based frameworks. They showcase how AI agents can integrate external data and functionality to deliver intelligent responses and solve real-world problems.

---

## AI Agents Built in This Project

This project includes three distinct AI agents. Each demonstrating a different level of complexity and automation:

| **Agent Type**         | **Automation Level** | **Scope**               | **Example Use Case**                              |
|-------------------------|----------------------|-------------------------|--------------------------------------------------|
| **Hardcoded Agent**     | Manual integration   | General-purpose         | Basic weather queries (manual function calls).  |
| **ReAct Framework Agent** | Fully automated       | Dynamic decision-making | Automated weather or general inquiries.         |
| **SEO Audit Agent**     | Fully automated       | Domain-specific (SEO)   | Analyzing and optimizing webpage performance.    |

These examples highlight progressively advanced implementations of AI agents. They start with a **hardcoded agent** and culminating in a specialized **SEO Audit AI Agent**.

---

## Agent Descriptions

### 1. Hardcoded AI Agent
- **Description:**  
  A basic example of an AI agent with predefined functionality to introduce the core concepts.
- **Features:**  
  - Uses static functions and hardcoded logic to generate responses.
  - Demonstrates how external tools can be manually integrated into AI workflows.
- **Example Use Case:**  
  *"Should I take an umbrella in California?"*  
  - A hardcoded weather function provides data that the agent integrates into its response.

---

### 2. ReAct Framework AI Agent
- **Description:**  
  A more advanced AI agent that utilizes the **ReAct Framework** to dynamically execute actions.
- **Features:**  
  - Implements a "Thought → Action → Action Response" loop.
  - Dynamically selects and executes appropriate functions based on the user query.
  - Capable of handling a variety of weather-related inquiries.
- **Example Use Case:**  
  *"What’s the weather in New York?"*  
  - The agent identifies the need for weather data, calls a weather API, and integrates the result into a meaningful response.

---

### 3. SEO Audit AI Agent
- **Description:**  
  A domain-specific AI agent designed for SEO analysis and webpage performance optimization.
- **Features:**  
  - Integrates external APIs to fetch SEO data like load times, image counts, and keyword analysis.
  - Tailored for tasks such as evaluating webpage performance and providing optimization recommendations.
- **Example Use Case:**  
  *"How many images are on the webpage example.com?"*  
  - The agent fetches data from an SEO API and generates insights specific to the user query.

---

## Key Takeaways

- **Automation Levels:** The project progresses from manual integration (Hardcoded Agent) to fully automated agents (ReAct Framework and SEO Audit).
- **Practical Use Cases:** Each agent serves a specific purpose. This ranges from answering basic queries to solving real-world problems like SEO analysis.
- **Dynamic Decision-Making:** The ReAct framework enables agents to understand tasks, select tools, and integrate results seamlessly.


## Future Work

- Expand functionality to include more domain-specific agents such as financial analysis, medical diagnostics, etc.
- Optimize existing agents to support multi-functionality.
- Integrate additional APIs to enhance agent capabilities.

