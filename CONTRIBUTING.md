# Contributing

Thanks for your interest! Small, focused contributions are welcome.

## Ground rules

- Open an issue first for anything larger than a typo fix, so we can agree on direction.
- Keep pull requests small and single-purpose.
- Contributions are licensed under the project's existing license.

## Development setup

Python projects:

```
python -m venv .venv && source .venv/bin/activate
pip install -e .[dev]
pytest
ruff check . && ruff format --check .
mypy src
```

JavaScript / browser projects:

```
npm install
npm test
```

## Pull request checklist

- [ ] Tests pass locally and new behavior is covered by a test.
- [ ] Linters and type checks pass (ruff, mypy, or the project's configured tools).
- [ ] README / CHANGELOG updated when behavior changes.
- [ ] No secrets, tokens, or personal paths in the diff.
- [ ] Claims in docs match what is actually tested; mark the rest as experimental.
