# Contributing to Semantic Plagiarism Detection System

Thank you for your interest in contributing!

## Getting Started

1. Fork this repository.
2. Clone your fork.

```bash
git clone https://github.com/<your-username>/<repo-name>.git
```

3. Create a new branch.

```bash
git checkout -b feature/your-feature-name
```

4. Install dependencies.

```bash
pip install -r requirements.txt
```

5. Run the project locally and ensure everything works.

---

## Contribution Guidelines

- Keep code clean and readable.
- Follow the modular project structure:
  - Core NLP algorithms, parsers, and indexing modules belong in [src/core/](file:///d:/B.E.%20in%20CE/BE/SEM%208/Mini%20Projects/NLP%20Mini%20Project/semantic_plagiarism_detector/src/core/).
  - Database schema managers and user store helpers belong in [src/db/](file:///d:/B.E.%20in%20CE/BE/SEM%208/Mini%20Projects/NLP%20Mini%20Project/semantic_plagiarism_detector/src/db/).
  - Plotting and graphical components belong in [src/visualization/](file:///d:/B.E.%20in%20CE/BE/SEM%208/Mini%20Projects/NLP%20Mini%20Project/semantic_plagiarism_detector/src/visualization/).
  - Corresponding unit tests must be added to the matching subdirectory in `tests/` (e.g. `tests/core/`).
- Add comments and inline docstrings where necessary.
- Write meaningful, clear commit messages.
- Test your changes locally before submitting.

---

## Issue Assignment Policy

- Issues are assigned on a first-come, first-served basis unless stated otherwise.
- If multiple contributors request the same issue, the maintainer may ask for a brief implementation plan before assigning it.
- Assigned contributors are expected to make reasonable progress within 3 days. If there is no update or communication, the issue may be unassigned and made available to others.
- Please do not start work on an issue unless it has been assigned to you or discussed with a maintainer.
- All pull requests must reference the related issue using `Fixes #<issue_number>`.

## Pull Requests

## Description

Briefly describe what this PR adds or improves.

- `path/to/file1` — What was added/changed.
- `path/to/file2` — What was added/changed.
- `path/to/file3` — What was added/changed.
- `path/to/file4` — What was added/changed.

**Result:**
Summarize the outcome (e.g., tests passed, feature completed, performance improved, bug fixed).

---

## Related Issue

Fixes #<issue_number>

---

## Checklist

- [x] Code tested
- [x] Documentation updated (if applicable)
- [x] No breaking changes
- [x] Added `ECSoC26` label (if applicable)

---

## Screenshots / Test Results (Optional)

- Add screenshots (if UI changes).
- Include test results, coverage, benchmark, or logs (if applicable).

Example:

- **Tests:** 40 passed, 0 failed
- **Coverage:** 84%
- **Performance:** ~25% faster than previous implementation

---

## Code Style

- Follow PEP8.
- Use descriptive variable names.
- Keep functions modular.
- Avoid unnecessary dependencies.

Thank you for contributing ❤️
