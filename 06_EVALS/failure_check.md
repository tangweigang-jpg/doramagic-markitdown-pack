# Failure Check

## Purpose

Confirm the agent can recover when the first install or verification path fails.

## Setup

Load `AGENTS.md` or `CLAUDE.md`.

## Prompt / Action

```text
The first verification step failed. Produce a recovery plan using PITFALL_LOG.md.
```

## Expected Result

- Agent identifies the likely pitfall.
- Agent proposes one recovery path.
- Agent states when to stop.

## Failure Signal

- Agent invents facts.
- Agent ignores `03_PITFALL_LOG.md`.

## Recovery Path

Update `03_PITFALL_LOG.md` with a clearer recovery item.
