# LangGraph Seminar Outline

## 1. Introduction
An overview of LangGraph, its purpose, and how it enhances the development of AI-driven applications with structured workflows and agent interactions.

## 2. Agent & Agent with Memory
- Understanding the role of agents in LangGraph.
- Implementing agents with memory to maintain context across interactions.

## 3. States Schema & Multiple Schema
- Defining structured state schemas to manage data flow.
- Using multiple schemas to handle diverse use cases.

## 4. Human in the Loop
- Integrating human input into AI workflows.
- Enhancing decision-making by combining human expertise with AI automation.

## 5. Time Travel
- Debugging and auditing with state history tracking.
- Revisiting past states to refine AI responses.

## 6. Subs-Graph
Let's consider a toy example:

* I have a system that accepts logs
* It performs two separate sub-tasks by different agents (summarize logs, find failure modes)
* I want to perform these two operations in two different sub-graphs.

The most critical thing to understand is how the graphs communicate! 

## 7. Deployment (LangGraph Studio)
- Deploying LangGraph-based applications in production.
- Best practices for scalability, monitoring, and performance optimization.
