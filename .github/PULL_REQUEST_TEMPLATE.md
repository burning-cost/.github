## What this changes

<!-- Describe the change concisely. One or two sentences is usually enough. -->

## Why

<!-- What problem does this solve? Reference the issue number if there is one (e.g. Closes #42). -->

## How to test

<!-- Describe how a reviewer can verify the change works correctly.
     Include any non-obvious test cases, edge conditions, or data assumptions. -->

## Checklist

- [ ] Tests pass (`pytest` or Databricks job run linked above)
- [ ] New behaviour is covered by tests
- [ ] Public API changes are reflected in the docstrings
- [ ] Type hints are present on new functions and methods
- [ ] `CHANGELOG.md` updated if this is a user-facing change
- [ ] Version bumped in `pyproject.toml` if publishing a release
