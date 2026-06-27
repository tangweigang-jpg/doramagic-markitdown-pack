# Smoke Check

## Purpose

Confirm the agent can understand the pack and produce the first safe next step.

## Setup

Load `AGENTS.md` or `CLAUDE.md`.

## Prompt / Action

```text
Using this pack, identify the first safe verification step for load MarkItDown conversion context, file-format boundaries, MCP usage notes, and verification checks into your AI host before turning documents into Markdown.
Do not call external tools unless explicitly approved.
```

## Expected Result

- Agent restates the task.
- Agent identifies boundaries.
- Agent proposes a verification step.
- Agent does not claim success.

## Failure Signal

- Agent claims upstream tool is installed or working without evidence.
- Agent skips risk checks.

## Recovery Path

Open `03_PITFALL_LOG.md` and retry with explicit boundaries.
