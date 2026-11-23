# Lab 5 — Governed MCP Connector

## Objective

Provides a typed, authenticated connector front door for course data sources using MCP.

## Implementation files

The following are the lab-specific source files, tests, notebook(s), and/or documentation copied from the original repository while preserving their original relative paths:

- `code/src/course_organizer/labs/lab05_mcp_connector.py`
- `code/src/course_organizer/connector/core.py`
- `code/src/course_organizer/connector/client.py`
- `code/src/course_organizer/connector/auth.py`
- `code/src/course_organizer/connector/port.py`
- `code/src/course_organizer/connector/mcp_server.py`
- `code/src/course_organizer/connector/adapters.py`
- `code/src/course_organizer/connector/endpoints.py`
- `code/src/course_organizer/connector/errors.py`
- `code/src/course_organizer/connector/__init__.py`
- `code/tests/test_lab05_lab_module.py`
- `code/tests/test_lab05_mcp_connector.py`
- `code/notebooks/lab05_mcp_connector.ipynb`
- `code/docs/lab05.md`
- `code/docs/evidence/lab05_notebook_output.txt`
- `code/docs/evidence/lab05_pytest.txt`
- `code/docs/evidence/lab05_cli.txt`
- `code/docs/evidence/lab05_cli_no_mcp.txt`

## Run / test notes

Run from the **repository root** after installing the project's dependencies:

```powershell
python -m course_organizer.labs.lab05_mcp_connector
```

**Shared dependencies:** Some lab code imports common modules from `src/course_organizer`, `api`, `models`, and `services`. Those shared project files remain in the repository root. Keep the original project structure and install the project using the root `requirements.txt` and `pyproject.toml`; these lab folders are organized copies for review, not independent pip packages.

## Scope note

This folder contains code and evidence found in the uploaded repository. It does not claim that files absent from the source ZIP were implemented.
