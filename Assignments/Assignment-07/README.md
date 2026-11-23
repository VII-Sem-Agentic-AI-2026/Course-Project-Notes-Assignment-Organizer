# Lab 7 — Agentic Node Graph

## Objective

Connects the core course-organizer workflow into an explicit stateful graph with validation, bounded retries, a faculty gate, and publication.

## Implementation files

The following are the lab-specific source files, tests, notebook(s), and/or documentation copied from the original repository while preserving their original relative paths:

- `code/src/course_organizer/labs/lab07_node_graph.py`
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
- `code/tests/test_lab07_graph.py`
- `code/tests/test_lab07_runner.py`
- `code/notebooks/lab07_node_graph.ipynb`
- `code/docs/lab07.md`
- `code/docs/evidence/lab07_notebook_output.txt`
- `code/docs/evidence/lab07_pytest.txt`
- `code/docs/evidence/lab07_cli.txt`

## Run / test notes

Run from the **repository root** after installing the project's dependencies:

```powershell
python -m course_organizer.labs.lab07_node_graph
```

**Shared dependencies:** Some lab code imports common modules from `src/course_organizer`, `api`, `models`, and `services`. Those shared project files remain in the repository root. Keep the original project structure and install the project using the root `requirements.txt` and `pyproject.toml`; these lab folders are organized copies for review, not independent pip packages.

## Scope note

This folder contains code and evidence found in the uploaded repository. It does not claim that files absent from the source ZIP were implemented.
