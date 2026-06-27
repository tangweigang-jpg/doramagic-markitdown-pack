# Contributing

This repository is an independent Doramagic AI context resource pack for the upstream project named in `SOURCE_MAP.md`.

Use issues for:

- Pack bugs: broken links, invalid instructions, failed evals, or missing files.
- Pitfall reports: setup, permission, runtime, or recovery failures that should be added to `03_PITFALL_LOG.md`.
- Usage questions: how to load this pack into Claude Code, Codex, Cursor, Aider, or another AI coding host.

Do not use this repository as the upstream project's support tracker. If the bug is in the upstream project itself, report it to the upstream repository first and link the upstream issue here only when it changes this pack.

Before opening an issue:

1. Read `README.md`, `00_QUICK_START.md`, and `03_PITFALL_LOG.md`.
2. Run the relevant check under `06_EVALS/`.
3. Include host, OS, command output, and the exact file or instruction that failed.

Pull requests should be small, evidence-backed, and scoped to the pack. Do not add generated bulk changes unless they are reproducible through the pack generation workflow.
