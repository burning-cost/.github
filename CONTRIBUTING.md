# Contributing

We welcome bug reports, questions, and pull requests.

## Reporting Issues

Use GitHub Issues. Before opening one, search existing issues to avoid duplicates.
Include a minimal reproducible example where possible. If you are reporting a
bug in numerical output, tell us what you expected and what you got.

Use GitHub Discussions for open-ended questions or methodology discussions.

## Contributing Code

1. Fork the repository and create a branch from `main`.
2. Make your changes. Keep commits focused — one logical change per commit.
3. Add or update tests to cover your change.
4. Run the test suite: `uv sync --all-extras && uv run pytest`
5. Open a pull request against `main`. Describe what you changed and why.

All CI checks must pass before merge. If you are unsure about approach,
open a Discussion first — it saves everyone time.

## Dev Setup

```bash
git clone https://github.com/burning-cost/<repo>.git
cd <repo>
uv sync --all-extras
uv run pytest
```

Python 3.10+ is required. Dependencies are pinned in `uv.lock`.

## Code Style

- Type hints on all public functions and methods.
- Docstrings on public API. One sentence summary, then detail if needed.
- UK English in documentation and docstrings (e.g. "modelling", "normalise").
- No line length pedantry, but keep lines readable.
- No linter will reject your PR for style alone — but reviewers may ask for
  changes if the code is hard to follow.

## Licensing

By submitting a pull request you agree that your contribution is licensed
under the MIT licence, the same licence as the project.
