# Agents

## What Is an Agent?

An **agent** is a software system that can perceive its environment, make decisions, and take actions to achieve a goal with some degree of autonomy. Modern AI agents are built on top of large language models (LLMs) and can reason, plan, use tools, and act on a user's behalf instead of just answering a single question.

In short: a chatbot responds, an **agent acts**.

## Core Capabilities

- **Reasoning & Planning** - Break a high-level goal into smaller, ordered steps.
- **Tool Use** - Call external tools, APIs, databases, or run code to get things done.
- **Memory** - Keep track of context across steps (and sometimes across sessions).
- **Autonomy** - Decide the next action without needing a human prompt at every step.
- **Feedback Loop** - Observe the result of an action and adjust the next one.

## How an Agent Works

A typical agent runs in a loop until the goal is reached:

1. **Goal** - The user gives a task or objective.
2. **Plan** - The agent decides what steps are needed.
3. **Act** - It executes a step, often by calling a tool.
4. **Observe** - It reads the result of that action.
5. **Reflect** - It checks progress and updates the plan.
6. **Repeat** - It loops until the goal is complete, then returns the result.

## Key Components

- **Model (LLM)** - The "brain" that reasons and generates decisions.
- **Tools** - Functions the agent can call (search, code execution, file edits, API calls).
- **Memory** - Short-term context and optional long-term storage.
- **Orchestrator** - The logic that runs the perceive-decide-act loop.

## Types of Agents

- **Single-step assistants** - Answer or perform one action at a time.
- **Autonomous agents** - Run multi-step tasks on their own until done.
- **Multi-agent systems** - Several specialized agents collaborate, each handling part of a task.

## Common Use Cases

- Writing, reviewing, and debugging code.
- Researching and summarizing information.
- Automating repetitive workflows.
- Interacting with APIs and external systems.
- Acting as customer support or personal assistants.

## Benefits and Challenges

**Benefits**

- Save time by automating multi-step work.
- Handle complex tasks with less human input.
- Integrate with many tools and systems.

**Challenges**

- Can make mistakes or "hallucinate" incorrect actions.
- Need guardrails and oversight for safety.
- Cost and reliability depend on the underlying model and tools.

## Summary

An agent is an AI system that doesn't just answer questions, it **takes action**. By combining reasoning, tools, memory, and an act-observe-reflect loop, agents can plan and complete real-world tasks with growing autonomy.