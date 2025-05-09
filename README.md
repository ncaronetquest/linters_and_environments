# Python Linters & Environments Demo

This repository demonstrates how to use modern Python linting and environment tools such as **Ruff**, **Black**, and **UV**.

## 📂 Structure

- `pre_ruff.py` – Contains poorly formatted code for demonstration.
- `post_ruff.py` – Contains poorly formatted code that will be formated and linted for demonstration.
- `.venv/` – Will be created by `uv init` (not tracked in version control).

## 🧪 Tools Used

| Tool     | Purpose               | Notes                          |
|----------|------------------------|-------------------------------|
| Ruff     | Linting & auto-fixes   | Very fast, many rules built-in |
| Black    | Code formatting        | Opinionated and consistent     |
| UV       | Environment management | Replaces pip, venv, virtualenv |

Make sure uv is installed. If not, install it from https://github.com/astral-sh/uv.

# ✅ Goals
Understand the value of linting.

Learn how to set up isolated environments.

Use modern tools to keep code clean and consistent.
