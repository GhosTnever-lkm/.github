# Security Policy

## Supported versions

Only the latest release (or the current `main` branch) of each repository receives
security fixes. Older releases are not patched.

## Reporting a vulnerability

Please do **not** open a public issue for a security problem.

- Use the repository's **Security → Report a vulnerability** button
  (GitHub private vulnerability reporting), or
- if that is unavailable, start a report titled `Security: <short summary>`
  and ask for a private contact before sharing details.

Please include: the affected repository and version, steps to reproduce,
the impact, and a proof of concept if you have one.

## Scope notes

- Many of these projects are defensive or local-first tools (scanners, linters,
  offline checkers). Findings about unsafe archive handling, secret leakage,
  or unexpected network activity are especially welcome.
- Never include real secrets, tokens, or personal data in a report.

Reports are read by the maintainer. There is no bug bounty; credit in the
release notes is given on request.
