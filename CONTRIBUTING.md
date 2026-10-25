# Contributing

Thanks for your interest! Small, focused contributions are welcome.

## Ground rules

- Open an issue first for anything larger than a typo fix, so we can agree on direction.
- Keep pull requests small and single-purpose.
- Contributions are licensed under the project's existing license.

## Development setup

First read the target repository's README and any repository-specific contribution guide. Its documented setup and checks take precedence over these general examples. Not every repository uses the same test runner, linter, type checker, or package layout.

Python project example (PowerShell):

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -e ".[dev]"
.\.venv\Scripts\python.exe -m pytest
```

Use the test command declared by that project. Run lint and type checks only when its configuration provides them; paths and optional dependency groups vary between projects.

JavaScript or browser project example:

```
npm ci
npm test
```

If the repository has no lockfile, use its documented install command instead of `npm ci`. If it has no `test` script, follow its README for the available checks.

## Pull request checklist

- [ ] The repository's documented tests and configured checks pass locally; new behavior is covered by a test when applicable.
- [ ] Configured linters and type checks pass, if the repository uses them.
- [ ] README / CHANGELOG updated when behavior changes.
- [ ] No secrets, tokens, or personal paths in the diff.
- [ ] Claims in docs match what is actually tested; mark the rest as experimental.
