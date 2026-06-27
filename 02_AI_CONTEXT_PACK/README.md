# AI Context Pack

## Pack Identity

- Upstream: https://github.com/microsoft/markitdown
- Pack type: Document Conversion Context Pack
- Doramagic canonical: https://doramagic.ai/en/projects/markitdown/
- Relationship: independent pack; not affiliated or endorsed unless explicitly stated.

## Operating Rules

- Evidence first.
- No official endorsement claim.
- Run evals before claiming success.
- Use pitfall and risk files for recovery.

## Host Files

- `../AGENTS.md`
- `../CLAUDE.md`

## Doramagic Source Extract

# markitdown - Doramagic AI Context Pack

> Purpose: pre-work context for the user's host AI. This pack does not prove that the project has been installed, run, or validated.

## Project

- canonical_name: `microsoft/markitdown`
- capability: Python tool for converting files and office documents to Markdown.
- expected_user_outcome: Python tool for converting files and office documents to Markdown.

## Operating Boundaries

- Do not claim that the project has been installed, run, called through an API, or used on local files unless separate evidence proves it.
- Project facts must come from repo evidence, Claim Graph, or explicit source references.
- When a capability is not verified, mark it as unverified instead of completing it as fact.
- publish_status: `publishable`
- blocking_gaps: none

---

## Doramagic Context Augmentation

The following sections strengthen the repository context for a host AI. Human Manual data is a reading route, and pitfall notes become operating constraints.

## Human Manual Outline

Usage rule: this is only a reading route and salience signal, not factual authority. Concrete claims must still return to repo evidence or Claim Graph.

Host AI hard rules:
- Do not treat page titles, section order, summaries, or importance values as factual project evidence.
- When explaining the Human Manual outline, state that it is only a reading route or salience signal.
- Capability, installation, compatibility, runtime state, and risk claims must cite repo evidence, source paths, or Claim Graph.

- **MarkItDown Overview and Core Architecture**: importance `high`
  - source_paths: README.md, packages/markitdown/src/markitdown/_markitdown.py, packages/markitdown/src/markitdown/_base_converter.py, packages/markitdown/src/markitdown/_stream_info.py, packages/markitdown/src/markitdown/_uri_utils.py
- **Built-in Format Converters and Known Limitations**: importance `high`
  - source_paths: packages/markitdown/src/markitdown/converters/_pdf_converter.py, packages/markitdown/src/markitdown/converters/_docx_converter.py, packages/markitdown/src/markitdown/converters/_pptx_converter.py, packages/markitdown/src/markitdown/converters/_xlsx_converter.py, packages/markitdown/src/markitdown/converters/_image_converter.py
- **AI, OCR, and Cloud Integrations**: importance `high`
  - source_paths: packages/markitdown/src/markitdown/converters/_llm_caption.py, packages/markitdown/src/markitdown/converters/_doc_intel_converter.py, packages/markitdown/src/markitdown/converters/_cu_converter.py, packages/markitdown-ocr/README.md, packages/markitdown-ocr/src/markitdown_ocr/_plugin.py
- **Deployment, MCP Server, and Plugin Extensibility**: importance `medium`
  - source_paths: packages/markitdown/src/markitdown/__main__.py, Dockerfile, packages/markitdown-mcp/README.md, packages/markitdown-mcp/src/markitdown_mcp/__main__.py, packages/markitdown-mcp/src/markitdown_mcp/__init__.py

## Repo Inspection Evidence

- repo_clone_verified: true
- repo_inspection_verified: true
- repo_commit: `e144e0a2be95b34df17433bac904e635f2c5e551`
- inspected_files: `Dockerfile`, `README.md`, `packages/markitdown/README.md`, `packages/markitdown/ThirdPartyNotices.md`, `packages/markitdown/pyproject.toml`, `packages/markitdown/src/markitdown/__about__.py`, `packages/markitdown/src/markitdown/__init__.py`, `packages/markitdown/src/markitdown/__main__.py`, `packages/markitdown/src/markitdown/_base_converter.py`, `packages/markitdown/src/markitdown/_exceptions.py`, `packages/markitdown/src/markitdown/_markitdown.py`, `packages/markitdown/src/markitdown/_stream_info.py`, `packages/markitdown/src/markitdown/_uri_utils.py`, `packages/markitdown/src/markitdown/converter_utils/__init__.py`, `packages/markitdown/src/markitdown/converter_utils/docx/__init__.py`, `packages/markitdown/src/markitdown/converter_utils/docx/math/__init__.py`, `packages/markitdown/src/markitdown/converter_utils/docx/math/latex_dict.py`, `packages/markitdown/src/markitdown/converter_utils/docx/math/omml.py`, `packages/markitdown/src/markitdown/converter_utils/docx/pre_process.py`, `packages/markitdown/src/markitdown/converters/__init__.py`

Host AI hard rules:
- Without repo_clone_verified=true, do not claim that the source code has been read.
- Without repo_inspection_verified=true, do not write README, docs, or package-file conclusions as facts.
- Without quick_start_verified=true, do not claim that the Quick Start path has run successfully.

## Doramagic Pitfall Constraints

These rules come from Doramagic discovery, validation, or compilation findings. The host AI must treat them as operating constraints, not background notes.

### Constraint 1: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/microsoft/markitdown/issues/20
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 2: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/microsoft/markitdown/issues/2019
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 3: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/microsoft/markitdown/issues/1489
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 4: Configuration risk requires verification

- Trigger: Project evidence flags a configuration risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/microsoft/markitdown/issues/2004
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 5: Configuration risk requires verification

- Trigger: Project evidence flags a configuration risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/microsoft/markitdown/issues/2106
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 6: Runtime risk requires verification

- Trigger: Project evidence flags a runtime risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/microsoft/markitdown/issues/2136
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 7: Maintenance risk requires verification

- Trigger: Project evidence flags a maintenance risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/microsoft/markitdown/issues/1211
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 8: Security or permission risk requires verification

- Trigger: Project evidence flags a security or permission risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/microsoft/markitdown/issues/1585
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 9: Installation risk requires verification

- Trigger: Developers should check this installation risk before relying on the project: Support for .doc extensions
- Host AI rule: Before packaging this project, run the relevant install/config/quickstart check for: Support for .doc extensions. Context: Observed when using windows, linux
- Why it matters: Developers may fail before the first successful local run: Support for .doc extensions
- Evidence: failure_mode_cluster:github_issue | https://github.com/microsoft/markitdown/issues/23
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 10: Installation risk requires verification

- Trigger: Developers should check this installation risk before relying on the project: XLSX Conversion Fails: SheetView parameter 'showZeroes' incompatible with openpyxl 3.1.0+
- Host AI rule: Before packaging this project, run the relevant install/config/quickstart check for: XLSX Conversion Fails: SheetView parameter 'showZeroes' incompatible with openpyxl 3.1.0+. Context: Observed when using python, windows
- Why it matters: Developers may fail before the first successful local run: XLSX Conversion Fails: SheetView parameter 'showZeroes' incompatible with openpyxl 3.1.0+
- Evidence: failure_mode_cluster:github_issue | https://github.com/microsoft/markitdown/issues/2063
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

