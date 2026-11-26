# Architecture — web2-lab

<!-- graffino-agentic:begin v1 -->
> How this repo is built, generated from the code at backfill and kept current by
> whoever changes the structure. The code wins: when this page is wrong, fix it.
<!-- graffino-agentic:end -->

## Overview
web2-lab is in initial setup. Purpose, runtime architecture, and components will be defined once the stack is chosen (see Q-001, Q-002 in OPEN-QUESTIONS.md).

```text
[Client / Browser] <---> [web2-lab application]
```

## Parts
| Part | Path | Responsibility | Talks to |
|---|---|---|---|
| Docs & Ledger | docs/ | Agent knowledge, architecture, design guardrails | AI agents, developers |

## Data flow
1. Not established yet (pending Q-001 and Q-002).

## State and storage
| What | Where | Owner | Notes |
|---|---|---|---|
| Knowledge Ledger | docs/agents/ | Team | Git tracked |

## Configuration
| Name | Where set | Used by | Notes |
|---|---|---|---|
<!-- names only, never values -->

## Build, deploy, runtime
Runtime and deployment are not configured yet (see Q-002, Q-004).

## Boundaries
Security boundaries and external trust zones will be documented once backend/frontend boundaries are designed.
