# Workflow Orchestrator

A developer-first, Temporal-powered workflow orchestrator for long-running, human-in-the-loop processes.

Workflow Orchestrator focuses on **durable orchestration**, **explicit state**, and **human involvement**, without the legacy complexity of traditional BPM engines.

## Why this exists

Most workflow engines fall into one of two camps:

- **Code-first orchestrators** that struggle with human tasks and auditability
- **Classic BPM tools** that are heavy, XML-driven, and hostile to developers

Workflow Orchestrator sits in between:
- Built on Temporal for durability and correctness
- API-first and TypeScript-first
- Explicit about tradeoffs
- Designed for developers, not business analysts

## What it is good at

- Long-running workflows (days, weeks, months)
- Human approvals and interventions
- REST and SOAP integration
- Durable retries and timers
- Full audit trail

## What it is NOT

- A low-code platform
- A citizen-developer tool
- A visual scripting toy
- A replacement for CI/CD pipelines

## Architecture (high level)

- Temporal is the execution engine
- Workflow Orchestrator provides:
  - process definitions
  - a workflow interpreter
  - human task management
  - APIs and adapters
  - observability and audit

## Status

🚧 Early development — actively evolving.

See `docs/` for architecture and design decisions.