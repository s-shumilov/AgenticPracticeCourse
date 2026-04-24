# You did it!

!!! tip "Congratulations!"

    You've built a conversational agent grounded in real documentation, connected it to live automation tools, and validated it through four types of real conversations.

---

## What you built

You created a conversational agent in **Agent Builder** that answers questions about invoices and ServiceNow tickets in real time. You grounded it in UiPath Security documentation using a **Context Grounding** index, then connected it to both RPA and API tools published in **Orchestrator**. Finally, you tested it across a data query, an incident lookup, a write operation, and a knowledge question — watching each tool call happen live.

| Component | Role |
|-----------|------|
| **Conversational Agent** | Answers questions in real time, scoped to grounded knowledge and connected tools |
| **Context Grounding** | Anchors responses to UiPath Security documentation, with citable sources |
| **Orchestrator Tools** | Lets the agent retrieve invoice data and ServiceNow incident details on demand |
| **Prompts** | Guides users toward the questions the agent is built to answer |

---

## What's next?

When to use which agent type?

| | Autonomous | Conversational |
|-|------------|----------------|
| **Interaction model** | Single-turn, task execution based on an initial prompt | Multi-turn, back-and-forth dialogue |
| **Primary use cases** | Executing complex tasks from a defined, structured prompt | Real-time user support and assistance, interactive information gathering |
| **User input** | Single, structured prompt or command | Continuous chat messages, often with ambiguity |
| **Core strength** | Executing predefined processes and automated workflows | Maintaining conversation, understanding context, and handling nuances |

### 1. Deploy and share your agent

Publish your agent from **Agent Builder** and share the endpoint with a colleague. Try asking it questions outside the grounded scope — notice how it handles topics it shouldn't answer.

### 2. Review observability data

Open the observability dashboard in Agent Builder. Check conversation logs, tool call frequency, and user feedback to decide what to improve next.

---

## Keep iterating

**Broaden the knowledge base**

- Add more documentation indexes to the context grounding source and observe how the agent's coverage changes.

**Add more Orchestrator tools**

- Connect additional tools and connections (for example MCP servers).

**Refine the system prompt**

- Regularly revisit the system prompt based on data and feedback. Tighten the domain constraints, adjust tool usage rules, and see how the agent's behavior shifts.

---

## Learn more

| Resource | Description |
|----------|-------------|
| [Conversational Agents](https://docs.uipath.com/agents/automation-cloud/latest/user-guide/conversational-agents) | Overview of conversational agents in UiPath Agent Builder |
| [Getting Started](https://docs.uipath.com/agents/automation-cloud/latest/user-guide/conversational-agents-getting-started) | Step-by-step guide to creating your first conversational agent |
| [Agent Design](https://docs.uipath.com/agents/automation-cloud/latest/user-guide/conversational-agents-design) | Prompt configuration, tools, and grounding options |
| [Deployment](https://docs.uipath.com/agents/automation-cloud/latest/user-guide/conversational-agents-deployment) | How to publish and share a conversational agent |
| [Observability](https://docs.uipath.com/agents/automation-cloud/latest/user-guide/conversational-agents-observability) | Monitoring conversations and tool usage |
| [Managing Indexes](https://docs.uipath.com/orchestrator/automation-cloud/latest/user-guide/managing-indexes) | Setting up documentation indexes for context grounding |
