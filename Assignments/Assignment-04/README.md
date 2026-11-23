# Lab 4 — Memory and Retrieval

## Objective

Separates short-term run state from long-term archived course knowledge and supports tag/similarity retrieval.

## Implementation files

The following are the lab-specific source files, tests, notebook(s), and/or documentation copied from the original repository while preserving their original relative paths:

- `code/src/course_organizer/labs/lab04_memory_retrieval.py`
- `code/src/course_organizer/memory/base.py`
- `code/src/course_organizer/memory/embeddings.py`
- `code/src/course_organizer/memory/retrieval.py`
- `code/src/course_organizer/memory/stores.py`
- `code/tests/test_lab04_memory_retrieval.py`
- `code/notebooks/lab04_memory_retrieval.ipynb`
- `code/docs/lab04.md`
- `code/docs/evidence/lab04_notebook_output.txt`
- `code/docs/evidence/lab04_pytest.txt`
- `code/docs/evidence/lab04_cli_hashing.txt`
- `code/docs/evidence/lab04_cli_fastembed.txt`

## Run / test notes

Run from the **repository root** after installing the project's dependencies:

```powershell
python -m course_organizer.labs.lab04_memory_retrieval
```

**Shared dependencies:** Some lab code imports common modules from `src/course_organizer`, `api`, `models`, and `services`. Those shared project files remain in the repository root. Keep the original project structure and install the project using the root `requirements.txt` and `pyproject.toml`; these lab folders are organized copies for review, not independent pip packages.

## Scope note

This folder contains code and evidence found in the uploaded repository. It does not claim that files absent from the source ZIP were implemented.
