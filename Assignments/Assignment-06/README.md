# Lab 6 — Governed Agent Runtime

## Objective

Wraps execution with budgets, approval gates, checkpoints, resume support, and audit logging.

## Implementation files

The following are the lab-specific source files, tests, notebook(s), and/or documentation copied from the original repository while preserving their original relative paths:

- `code/src/course_organizer/labs/lab06_governed_runtime.py`
- `code/src/course_organizer/runtime/runtime.py`
- `code/src/course_organizer/runtime/checkpoint.py`
- `code/src/course_organizer/runtime/gates.py`
- `code/src/course_organizer/runtime/budget.py`
- `code/src/course_organizer/runtime/audit.py`
- `code/src/course_organizer/runtime/errors.py`
- `code/src/course_organizer/runtime/__init__.py`
- `code/tests/test_lab06_lab_module.py`
- `code/tests/test_lab06_runtime.py`
- `code/notebooks/lab06_governed_runtime.ipynb`
- `code/docs/lab06.md`
- `code/docs/evidence/lab06_notebook_output.txt`
- `code/docs/evidence/lab06_pytest.txt`
- `code/docs/evidence/lab06_cli.txt`

## Run / test notes

Run from the **repository root** after installing the project's dependencies:

```powershell
python -m course_organizer.labs.lab06_governed_runtime
```

**Shared dependencies:** Some lab code imports common modules from `src/course_organizer`, `api`, `models`, and `services`. Those shared project files remain in the repository root. Keep the original project structure and install the project using the root `requirements.txt` and `pyproject.toml`; these lab folders are organized copies for review, not independent pip packages.

## Scope note

This folder contains code and evidence found in the uploaded repository. It does not claim that files absent from the source ZIP were implemented.
