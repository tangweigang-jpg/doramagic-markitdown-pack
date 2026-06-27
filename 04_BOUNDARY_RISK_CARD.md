# Boundary & Risk Card

## Permissions

- Browser:
- Network:
- Filesystem:
- Credentials:
- External services:

## Hard Boundaries

- Do not use secrets without explicit user approval.
- Do not claim production safety without passing evals.
- Do not imply upstream endorsement.

## Known Risks

- External tool or browser access may expose sensitive state if used without boundaries.
- Host compatibility and installed version must be verified before real use.

## Stop Conditions

- Unknown license.
- Failed dogfooding.
- Missing source attribution.
- Tool permission unclear.

## Doramagic Source Extract

# Boundary & Risk Card

Project: microsoft/markitdown

## Doramagic Trial Decision

Current decision: ready for pre-publication recommendation checks. First use should still start with least privilege, a temporary directory, and rollback.

## What The User Can Do Now

- Read the Human Manual first to understand purpose and main workflows.
- Copy the Prompt Preview for a pre-install trial. This checks interaction feel, not real execution.
- Test the official Quick Start command in an isolated environment before using a primary machine.

## What Not To Do Yet

- Do not treat Prompt Preview output as an actual project run.
- Do not treat metadata-only validation as sandbox install validation.
- Do not write unverified capabilities as supported, tested, or safe to install.
- Do not provide production data, private files, real secrets, or primary configuration directories on first use.

## Pre-install Checklist

- Host AI match: chatgpt
- Official install entry state: official entry found
- Verification location: temporary directory, temporary host, or container required
- Rollback readiness: required
- API keys, network access, file writes, or host configuration changes: treat as high risk until confirmed
- Install command, actual output, and failure logs: must be recorded

## Current Blockers

- No blockers.

## Project-specific Pitfalls

- Installation risk requires verification (high): May increase setup, validation, or first-run risk for the user. Suggested check: Reproduce the official install and quickstart path in an isolated environment.
- Installation risk requires verification (high): May increase setup, validation, or first-run risk for the user. Suggested check: Reproduce the official install and quickstart path in an isolated environment.
- Installation risk requires verification (high): May increase setup, validation, or first-run risk for the user. Suggested check: Reproduce the official install and quickstart path in an isolated environment.
- Configuration risk requires verification (high): May increase setup, validation, or first-run risk for the user. Suggested check: Reproduce the official install and quickstart path in an isolated environment.
- Configuration risk requires verification (high): May increase setup, validation, or first-run risk for the user. Suggested check: Reproduce the official install and quickstart path in an isolated environment.

## Risk And Permission Notes

- no_demo: medium

## Evidence Gaps

- No structured evidence gaps found.

