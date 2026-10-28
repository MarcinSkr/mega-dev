# Agent instructions

## Python environment

This repository is an Astral `uv` project, defined by `pyproject.toml`.
Use `uv` for all Python execution and dependency management:

- Run Python commands with `uv run python ...`.
- Run project commands with `uv run ...`.
- Add or remove dependencies with `uv add` or `uv remove`.
- Synchronize the environment with `uv sync`.

Do not use bare `python`, `pip`, or manually manage the `.venv`; `uv` must
select the Python version and project environment.

## Source layout

Application code lives under `src/mega_dev/`. The package currently
exposes the `main` entry point configured in `pyproject.toml`.
