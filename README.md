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
| Governance Layer | Approvals, escalation, accountability | Humans |



## Responsibility Engineering Lens

This repository applies a Responsibility Engineering approach to AI-enabled work:

| Question | Owner |
|----------|-------|
| What information should be remembered? | Organizational Memory |
| What may AI summarize or infer? | Intelligence Layer |
| What actions may AI take? | Execution Layer |
| What requires human approval? | Governance |
| Who remains accountable? | Humans |

> **AI assists. Humans approve.**

The goal is not autonomous decision-making. The goal is augmented execution with explicit accountability.



## Current Pilot

This pilot explores how an AI-enabled PMO can connect structured execution with organizational memory.

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



## Demo

### Operating Model

```text
             Organizational Memory
    (meetings, decisions, risks, artifacts)
                        ↕
               Intelligence Layer
     (AI summarization, retrieval, signals)
                        ↕
           Human & Agent Execution
    (planning, delivery, approvals, actions)
                        ↺
                Outcomes & Learning
```

### Example Artifacts

| Artifact | Purpose |
|----------|---------|
| Airtable Intake | Track requests, status, owners, and experiments |
| Obsidian Decision Note | Preserve rationale, tradeoffs, and risks |
| AI Summary | Surface signals and draft structured outputs |
| Human Review | Maintain accountability and decision rights |

> Coming Soon: screenshots of the Airtable base and Obsidian vault here as the pilot evolves.



## Success Criteria

The system is successful if a program item can be traced from:

**Request → Reasoning → Decision → Action → Outcome**

while preserving accountability at every step.



*This repository is an experiment in designing PMO systems for the AI era—where intelligence is augmented, context is preserved, and accountability remains human.*
