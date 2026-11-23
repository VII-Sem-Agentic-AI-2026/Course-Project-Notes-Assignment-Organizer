# Lab 12 — Safety, Governance, and Role Protection

## Objective

Tests authentication/role boundaries, release governance, rollback, and metrics confidentiality. The repository contains a dedicated test module; no separate Lab 12 design document was present in the ZIP.

## Implementation files

The following are the lab-specific source files, tests, notebook(s), and/or documentation copied from the original repository while preserving their original relative paths:

- `code/api/security.py`
- `code/api/deps.py`
- `code/api/routers/auth.py`
- `code/api/routers/releases.py`
- `code/api/routers/metrics.py`
- `code/models/auth.py`
- `code/models/release.py`
- `code/tests/test_lab12_governance.py`

## Run / test notes

The lab uses shared project modules. Run its tests from the repository root:

```powershell
python -m pytest tests/test_lab12_governance.py -q
```

**Shared dependencies:** Some lab code imports common modules from `src/course_organizer`, `api`, `models`, and `services`. Those shared project files remain in the repository root. Keep the original project structure and install the project using the root `requirements.txt` and `pyproject.toml`; these lab folders are organized copies for review, not independent pip packages.

## Scope note

This folder contains code and evidence found in the uploaded repository. It does not claim that files absent from the source ZIP were implemented.
