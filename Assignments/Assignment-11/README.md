# Lab 11 — Tested Build Factory

## Objective

Runs the graph using a validated authorized plan and returns a typed build/acceptance verdict; a passing build permits faculty review, not automatic approval.

## Implementation files

The following are the lab-specific source files, tests, notebook(s), and/or documentation copied from the original repository while preserving their original relative paths:

- `code/src/course_organizer/build.py`
- `code/src/course_organizer/graph/runner.py`
- `code/src/course_organizer/graph/state.py`
- `code/scripts/run_build.py`
- `code/tests/test_lab11_build.py`
- `code/docs/lab11.md`
- `code/docs/evidence/lab11_cli.txt`
- `code/docs/evidence/lab11_pytest.txt`

## Run / test notes

Run from the **repository root** after installing the project's dependencies:

```powershell
python -m scripts.run_build
```

**Shared dependencies:** Some lab code imports common modules from `src/course_organizer`, `api`, `models`, and `services`. Those shared project files remain in the repository root. Keep the original project structure and install the project using the root `requirements.txt` and `pyproject.toml`; these lab folders are organized copies for review, not independent pip packages.

## Scope note

This folder contains code and evidence found in the uploaded repository. It does not claim that files absent from the source ZIP were implemented.
