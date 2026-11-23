# Lab 10 — Self-Healing Validation

## Objective

Diagnoses validation failures, performs targeted bounded repairs, revalidates, and escalates unsafe or unrepairable cases.

## Implementation files

The following are the lab-specific source files, tests, notebook(s), and/or documentation copied from the original repository while preserving their original relative paths:

- `code/src/course_organizer/graph/repair.py`
- `code/src/course_organizer/graph/nodes.py`
- `code/src/course_organizer/graph/state.py`
- `code/src/course_organizer/graph/validation.py`
- `code/tests/test_lab10_self_heal.py`
- `code/docs/lab10.md`

## Run / test notes

The lab uses shared project modules. Run its tests from the repository root:

```powershell
python -m pytest tests/test_lab10_self_heal.py -q
```

**Shared dependencies:** Some lab code imports common modules from `src/course_organizer`, `api`, `models`, and `services`. Those shared project files remain in the repository root. Keep the original project structure and install the project using the root `requirements.txt` and `pyproject.toml`; these lab folders are organized copies for review, not independent pip packages.

## Scope note

This folder contains code and evidence found in the uploaded repository. It does not claim that files absent from the source ZIP were implemented.
