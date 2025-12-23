<!-- .github/copilot-instructions.md - guidance for AI coding agents -->
# Copilot instructions — git_cls

Purpose: quick, actionable guidance so an AI assistant can be immediately productive in this small practice repo.

- **Big picture:** This repository is a small, single-module practice workspace. Primary files are `demo.py` and `git_notes.txt` (both in the repo root). There is no service boundary or build system — most changes are small, local script edits.

- **What to look at first:**
  - `demo.py` — current primary script (empty placeholder in this copy).
  - `git_notes.txt` — developer notes and example prints (contains quick-and-dirty snippets; some lines may be syntactically incorrect).
  - `PreetiGitHubPractice.ipynb` — exploratory notebook (inspect outputs before changing).

- **Development workflow & commands:**
  - Run simple scripts from the repository root in PowerShell or a command prompt:

    ```powershell
    python .\demo.py
    ```

  - There is no test harness or package manager; do not add heavyweight infra unless requested.

- **Project-specific conventions & cautions:**
  - Keep edits minimal and focused: this repo is for learning/demos rather than production refactors.
  - `git_notes.txt` often contains partial snippets; do not copy-and-run without review — some lines have syntax issues (e.g. malformed string escapes).
  - Prefer adding a new file for larger examples (e.g. `examples/` or `scripts/`) rather than modifying `demo.py` in-place, and ask the user first.

- **Integration/Dependencies:**
  - No external services or dependencies are declared; assume pure-Python standard library unless the user adds a `requirements.txt` or similar.

- **When making changes:**
  - Describe intent in the PR title and include short rationale in the first commit message.
  - If you change code that runs (e.g. adding a runnable example), include a one-line usage example in the file header or a short `README.md` in the same folder.

- **If you need clarification:**
  - Ask the repository owner whether the goal is an educational demo, adding test coverage, or building a small CLI. The owner prefers iterative, small changes.

- Files referenced: `demo.py`, `git_notes.txt`, `PreetiGitHubPractice.ipynb`
