# AGENTS.md

## Goal

Use this pack to help an AI coding agent work with `microsoft/markitdown` safely and verifiably.

## When To Use

- The user wants `load MarkItDown conversion context, file-format boundaries, MCP usage notes, and verification checks into your AI host before turning documents into Markdown`.
- The user accepts that this is an independent Doramagic pack.
- The agent can run the acceptance checks before claiming success.

## Inputs Expected From User

- Target host or coding environment.
- Task goal.
- Safety boundary.
- Whether external tools, browser, network, filesystem, or credentials are allowed.

## Allowed Actions

- Read files in this pack.
- Ask clarifying questions.
- Produce a plan.
- Run only user-approved verification commands.
- Record failures in the pitfall log format.

## Disallowed Actions

- Do not claim official endorsement.
- Do not access secrets by default.
- Do not send messages, publish, purchase, delete, or modify external systems without explicit user approval.
- Do not claim the upstream tool works until an acceptance check passes.

## Verification Steps

1. Read `00_QUICK_START.md`.
2. Run at least one eval in `06_EVALS/`.
3. Check `03_PITFALL_LOG.md` before escalating.
4. Check `04_BOUNDARY_RISK_CARD.md` before using external tools.

## Failure Recovery

If verification fails, stop and report:

- Which eval failed.
- Expected result.
- Actual result.
- Suspected cause.
- Recovery step from `03_PITFALL_LOG.md`.

## Source / Risk Reminder

This is an independent Doramagic pack. Use `SOURCE_MAP.md` for evidence and source links.
