# Lab 13 — Domain Specialists and Human Gate

## Objective

Implements theory, lab, and project specialists, integrates specialist outcomes into the graph, and prevents publication when specialist or approval conditions fail.

## Implementation files

The following are the lab-specific source files, tests, notebook(s), and/or documentation copied from the original repository while preserving their original relative paths:

- `code/src/course_organizer/graph/specialists.py`
- `code/src/course_organizer/graph/specialists_theory.py`
- `code/src/course_organizer/graph/specialists_lab.py`
- `code/src/course_organizer/graph/specialists_project.py`
- `code/src/course_organizer/graph/registry.py`
- `code/src/course_organizer/graph/nodes.py`
- `code/src/course_organizer/graph/state.py`
- `code/tests/test_lab13_gate_publish.py`
- `code/tests/test_lab13_specialists.py`

## Run / test notes

The lab uses shared project modules. Run its tests from the repository root:

```powershell
python -m pytest tests/test_lab13_gate_publish.py tests/test_lab13_specialists.py -q
```

**Shared dependencies:** Some lab code imports common modules from `src/course_organizer`, `api`, `models`, and `services`. Those shared project files remain in the repository root. Keep the original project structure and install the project using the root `requirements.txt` and `pyproject.toml`; these lab folders are organized copies for review, not independent pip packages.

## Scope note

This folder contains code and evidence found in the uploaded repository. It does not claim that files absent from the source ZIP were implemented.
