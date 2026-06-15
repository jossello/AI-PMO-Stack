Create a simple Airtable base called "AI PMO Pilot" for a one-day experiment testing an AI-enabled program management workflow.

This is a lightweight pilot, not a production system. Keep the design simple and avoid advanced automations, formulas, or integrations.

Create exactly three tables:

## 1. Intake

Purpose: Capture ideas, requests, and work items entering the system.

Fields:

* Title (single line text)
* Problem Statement (long text)
* Priority (single select: Low, Medium, High)
* Status (single select: Idea, Reviewing, Decided, Done)
* Obsidian Note Link (URL)
* Notes (long text)

## 2. Decisions

Purpose: Capture important decisions and their rationale.

Fields:

* Decision Title (single line text)
* Linked Intake Item (linked record to Intake)
* Context (long text)
* Decision Made (long text)
* Tradeoffs (long text)
* Review Date (date)

## 3. Experiments

Purpose: Track AI experiments and learning.

Fields:

* Experiment Name (single line text)
* Hypothesis (long text)
* Success Criteria (long text)
* Failure Signals (long text)
* Outcome (long text)
* Status (single select: Planned, Running, Complete)

Create simple views:

* Intake by Status
* Open Experiments
* Recent Decisions

Do not create automations.

Do not create AI agents.

Do not automatically update records.

The goal of this pilot is to test the workflow:

Question → Capture → Think → Decide → Learn

This base should support human decision-making with AI assistance, not autonomous execution.
