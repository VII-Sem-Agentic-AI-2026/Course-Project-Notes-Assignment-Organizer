# Lab 14 — Integrated Capstone Demo

## Objective

Exercises the full workflow from request and specialist execution through validation/repair, faculty approval, publication, and dashboard status.

## Implementation files

The following are the lab-specific source files, tests, notebook(s), and/or documentation copied from the original repository while preserving their original relative paths:

- `code/scripts/run_lab14_demo.py`
- `code/src/course_organizer/graph/specialists_project.py`
- `code/src/course_organizer/graph/validation.py`
- `code/src/course_organizer/graph/specialists.py`
- `code/src/course_organizer/graph/specialists_lab.py`
- `code/src/course_organizer/graph/swarm.py`
- `code/src/course_organizer/graph/specialists_theory.py`
- `code/src/course_organizer/graph/builder.py`
- `code/src/course_organizer/graph/runner.py`
- `code/src/course_organizer/graph/context.py`
- `code/src/course_organizer/graph/registry.py`
- `code/src/course_organizer/graph/repair.py`
- `code/src/course_organizer/graph/__init__.py`
- `code/src/course_organizer/graph/escalation.py`
- `code/src/course_organizer/graph/state.py`
- `code/src/course_organizer/graph/nodes.py`
- `code/api/routers/runs.py`
- `code/services/graph_service.py`
- `code/tests/test_lab14_capstone.py`
- `code/tests/test_lab14_phase4_demo.py`
- `code/docs/lab14_phase4_demo.md`

## Run / test notes

Run from the **repository root** after installing the project's dependencies:

```powershell
python -m scripts.run_lab14_demo --domain lab
```

The demo pauses at the faculty gate. Resume with the run ID printed by the command and an explicit decision.

**Shared dependencies:** Some lab code imports common modules from `src/course_organizer`, `api`, `models`, and `services`. Those shared project files remain in the repository root. Keep the original project structure and install the project using the root `requirements.txt` and `pyproject.toml`; these lab folders are organized copies for review, not independent pip packages.

## Scope note

This folder contains code and evidence found in the uploaded repository. It does not claim that files absent from the source ZIP were implemented.
