# LAJBI Prompt Framework

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)
[![GitHub stars](https://img.shields.io/github/stars/LAJBY/LAJBI.svg)](https://github.com/LAJBY/LAJBI/stargazers)
[![Wiki](https://img.shields.io/badge/docs-wiki-blue.svg)](https://github.com/LAJBY/LAJBI/wiki)
<a href="https://github.com/LAJBY/LAJBI" target="_blank" rel="noopener noreferrer"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LAJBY/LAJBI/main/assets/powered-by-lajbi-dark.svg"><source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LAJBY/LAJBI/main/assets/powered-by-lajbi-light.svg"><img alt="Powered by LAJBI" src="https://raw.githubusercontent.com/LAJBY/LAJBI/main/assets/powered-by-lajbi-light.svg"></picture></a>

**LAJBI (Layered Architecture for Justification-Based Intelligence) is an advanced framework for interacting with and controlling AI. Think of it less like a chat and more like an operating system for AI agents.**

It uses a structured, command-based language to move beyond simple conversation and enable complex, reliable, and transparent operations with single or multiple AI agents.

---

## Why LAJBI?

Standard conversational prompts are often ambiguous and lack fine-grained control. LAJBI solves this by introducing a new paradigm built on three core principles:

1.  **🤖 From Conversation to Control**: Replace ambiguous natural language with a clear, declarative command syntax (`<command> KEYWORD:[parameter]`) for precise, repeatable results.
2.  **🤝 From a Single Assistant to a Team of Specialists**: Define and load a team of specialized AI agents (Personas) who collaborate and debate to solve complex problems.
3.  **🧠 From a Black Box to a Transparent Mind**: Every agent operates on the **PABIAM Cognitive Architecture**, making its reasoning process transparent and auditable.

---

## Key Features

* **Declarative Control Language**: A simple but powerful syntax for controlling AI actions.
* **Multi-Agent Collaboration**: Orchestrate teams of specialized AI agents who debate and reach a consensus.
* **Cognitive Transparency**: Inspect any agent's internal "mind" (its beliefs, intentions, and focus) using the PABIAM model.
* **Dynamic & Extensible**: Load new commands and behaviors in-session with extension modules.
* **Systematic Refinement**: Built-in tools to evaluate, interpret, and optimize your prompts.

---

## Getting Started

### 1. Initialize the Core

Start a session with the LAJBI framework. The system will load its core modules and signal readiness.

> **SYS_AI:** `LAJBI core ready.`

### 2. Load a Persona

Use the `<join>` command to add your first specialized agent.

> **USER:** `<join> TITLE: Python Coder NAME: Coder PROMPT: **Role:** You are an expert Python developer...`
>
> **SYS_AI:** `Persona 'Coder' has joined the team as 'Python Coder'.`

### 3. Interact with Your Agent

Address the agent directly using the `@` prefix to assign a task.

> **USER:** `@Coder write a Python function to find the factorial of a number.`
>
> **Coder:** `Of course. Here is a Python function...`

---

## Dive Deeper

This README provides a brief overview. For a complete guide, including the full command reference, architectural breakdown, and advanced examples, please visit our **[Official Project Wiki](https://github.com/LAJBY/LAJBI/wiki)**.

## Contributing

We welcome contributions to the LAJBI framework! Please see our `CONTRIBUTING.md` file for guidelines on how to submit issues, propose features, and contribute to the code.

## Supporting LAJBI (Optional)

If you find this framework useful, you can show your support by including a "Powered by LAJBI" badge in your project. While not required, it is greatly appreciated! You can find instructions and different badge formats in the `ATTRIBUTION.md` file.

## License

This project is licensed under the MIT License - see the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md) file for details.
