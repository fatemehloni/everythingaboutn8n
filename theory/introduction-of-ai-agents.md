# Introduction to AI Agents

## What is an Agent?

An AI agent is a system that can perceive its environment, make decisions, and take actions to achieve a specific goal.
Unlike a simple prompt-response model, an agent can operate over multiple steps and adapt its behaviour based on context and feedback.

In practice, agents combine reasoning, memory, and tool usage to solve tasks that are too complex for a single model response.

---

## How Agents Work

At a high level, an AI agent works in a loop:
1. Observe the environment and current state
2. Decide what to do next based on its goal
3. Use tools or generate actions
4. Evaluate the result and continue if needed

This loop allows agents to handle long-running, goal-oriented tasks rather than one-off questions.

---

## Agent Case Study: ChatGPT and Gemini

### ChatGPT
ChatGPT acts as an agent when it can:
- Maintain context across multiple turns
- Use tools such as browsing or code execution
- Break down complex tasks into smaller steps

In this mode, ChatGPT behaves less like a chatbot and more like a task-oriented assistant.

### Gemini
Gemini is designed as a multi-modal agent that can:
- Understand text, images, and other inputs
- Reason across different data types
- Interact with external tools and services

This makes it suitable for more complex, cross-domain tasks.

---

## Types of Agents

AI agents can be categorised based on how they interact with their environment and tools.

| Agent Type        | Environment                     | Tools                         | System Prompt Role |
|-------------------|----------------------------------|-------------------------------|--------------------|
| Assistant Agent   | Chat-based, user-driven          | Text generation, search       | Defines tone, role, and boundaries |
| Automation Agent  | Workflow or system environment   | APIs, scripts, external apps  | Defines goals and execution rules |
| Research Agent    | Document and data-rich context   | Search, summarization, memory | Defines research scope and output format |

Each agent type uses the same core components but applies them differently based on the problem being solved.

---

AI agents are the foundation of modern intelligent systems where reasoning, action, and iteration are required.
They are especially powerful when embedded into workflows and automation platforms.
