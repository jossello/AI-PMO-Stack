# AI PMO Stack

**AI-enabled PMO operating model combining organizational memory, AI-assisted intelligence, and human accountability. Demonstrates how Airtable, Obsidian, and AI agents preserve context, surface risks, support decisions, and improve cross-functional execution.**

## Overview

As AI becomes embedded in enterprise workflows, program management must evolve beyond status tracking and coordination. Modern PMOs increasingly need to manage not only work, but also context, decisions, risks, and accountability across humans and AI systems.

This repository explores an AI-enabled PMO operating model built around four principles:

- **Organizational Memory** — preserve context, decisions, and relationships over time
- **AI-Assisted Intelligence** — surface insights, summarize information, and identify risks
- **Human & Agent Execution** — coordinate work across people and AI systems
- **Human Accountability** — maintain clear ownership and decision rights

The core hypothesis is:

> **Organizational Memory → Intelligence Layer → Human & Agent Execution**

AI works best when it operates on structured context with explicit governance and human oversight.


## Why This Repository Exists

Traditional PM tools excel at tracking execution:

- What work is being done?
- Who owns it?
- When is it due?

They are often less effective at preserving:

- Why decisions were made
- What tradeoffs were considered
- Which assumptions existed
- How risks evolved over time

This repository explores how modern PMOs can combine operational systems with organizational memory to support AI-enabled work.


## Architecture

| Layer | Purpose | Example Tools |
|-------|---------|---------------|
| Organizational Memory | Preserve context, decisions, and relationships | Obsidian |
| Intelligence Layer | Summarize, classify, and detect signals | AI agents, LLMs, RAG |
| Execution Layer | Track work, owners, and status | Airtable, Jira |
| Governance Layer | Approvals, escalation, accountability | Human decision makers |


## Example Workflow

```text
Meeting Notes
      ↓
Decision Records
      ↓
AI Summarization & Risk Detection
      ↓
Airtable Tracking & Routing
      ↓
Human Review & Approval
      ↓
Execution & Learning
```


## Responsibility Engineering Lens

This repository applies a Responsibility Engineering approach to AI-enabled work:

| Question | Owner |
|----------|-------|
| What information should be remembered? | Organizational Memory |
| What may AI summarize or infer? | Intelligence Layer |
| What actions may AI take? | Execution Layer |
| What requires human approval? | Governance |
| Who remains accountable? | Humans |

The goal is not autonomous decision-making.

The goal is **augmented execution with explicit accountability**.


## Current Pilot

Initial implementation explores:

### Airtable
- Intake management
- Experiment tracking
- Decision register
- Risk tracking

### Obsidian
- Meeting notes
- Decision records
- Prompt library
- Project notes
- Experiment logs

### AI
- Summarization
- Structured extraction
- Risk flagging
- Pattern detection

**Rule:** AI assists. Humans approve.


## Success Criteria

The system is successful if a program item can be traced from:

**Request → Reasoning → Decision → Action → Outcome**

while preserving accountability at every step.



## Future Exploration

- AI-assisted dependency management
- Portfolio health monitoring
- Agent decision briefs
- Human-in-the-loop workflows
- AI observability and drift detection
- Program intelligence dashboards


*This repository is an experiment in designing PMO systems for the AI era—where intelligence is augmented, context is preserved, and accountability remains human.*
