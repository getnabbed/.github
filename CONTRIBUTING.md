# Contributing

Thanks for your interest in contributing to Nabbed. Each repository's README
says how to build and test it; this page covers what applies to all of them.

## Before you start

- Open an issue first for anything beyond a small fix, so the approach can be
  agreed before you spend significant time on it.
- Search existing issues and pull requests to avoid duplicate work.

## Pull requests

- Keep each pull request focused; split unrelated changes.
- Add or update tests for any behaviour you change.
- Run the repository's lint and test commands before pushing. CI runs the
  same checks.
- Write commit messages in the imperative mood, with a short summary line
  and a body that says why the change is needed.

## Reporting bugs

Open an issue in the repository concerned, with the version you run, what
you did, what you expected and what happened instead. For the agent, include
the output of `agent version` and the relevant log lines (they never contain
secrets).

## Security issues

Never open a public issue for a security vulnerability. See
[SECURITY.md](SECURITY.md).

## Code of conduct

All Nabbed projects follow the [Contributor Covenant](CODE_OF_CONDUCT.md).
