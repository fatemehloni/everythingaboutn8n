# Introduction to n8n

## What is Automation?

Automation is the process of executing tasks and processes automatically with minimal human intervention.
It focuses on replacing repetitive, manual work with systems that follow predefined rules and logic.

In software, automation helps reduce errors, save time, and improve consistency across operations.

---

## What is Intelligent Automation?

Intelligent automation goes one step further by combining automation with AI.
Instead of only following fixed rules, systems can make decisions, adapt to context, and handle unstructured data.

This allows workflows to process text, make predictions, classify data, and support human decision-making.

---

## What is n8n?

n8n is an open-source workflow automation platform.
It allows users to connect different services, APIs, and tools to automate processes using a visual interface.

n8n is especially powerful because it supports:
- Custom logic
- Code-based extensions
- Self-hosting
- Native AI integrations

---

## What is Canvas?

The canvas is the visual workspace where workflows are built in n8n.
It allows users to drag, drop, and connect nodes to define how data flows through a workflow.

The canvas provides a clear, visual representation of logic and execution order.

---

## What is a Workflow?

A workflow is a sequence of connected steps that define how data moves and actions are executed.
Each workflow starts with a trigger and continues through one or more nodes that process data.

Workflows can be simple (single-step) or complex (multi-branch and conditional).

---

## Types of Nodes in n8n

n8n workflows are built using three main types of nodes, each with a clear role in the execution flow.

### Trigger Nodes
Trigger nodes start a workflow.
They define *when* and *how* a workflow is executed, such as receiving a webhook, running on a schedule, or reacting to an external event.

### Condition Nodes
Condition nodes control the logic and branching of a workflow.
They evaluate data and decide which path the workflow should follow based on defined rules or expressions.

### Action Nodes
Action nodes perform operations.
They execute tasks such as calling APIs, transforming data, sending messages, or writing to external systems.

---

## Templates in n8n

Templates are pre-built workflows designed for common use cases.
They help users get started quickly without building workflows from scratch.

Templates can be customized and extended based on specific needs.

---

## Credentials in n8n

Credentials store authentication details required to connect to external services.
They allow secure access to APIs without exposing sensitive information inside workflows.

Credentials are reusable across multiple workflows.

---

## Using AI in n8n

n8n supports AI by integrating language models and AI services directly into workflows.
This makes it possible to:
- Generate or analyze text
- Classify and enrich data
- Build AI-powered automation flows

AI in n8n is used as a component inside workflows, not as a standalone system.
This enables practical, production-ready intelligent automation.
