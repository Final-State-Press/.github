# Contributing to Final State Press

Thank you for your interest in contributing. Final State Press projects span content engineering tools, knowledge systems, and open-source publishing. Whether you write code, improve documentation, report bugs, or propose ideas, your contribution matters.

This guide covers the basics. Individual repositories may have additional guidance in their own README or docs — check those first.

## Ways to contribute

**Report a bug.** Open an Issue in the relevant repository. Include what you expected to happen, what actually happened, and steps to reproduce. Logs, screenshots, or sample input files help enormously.

**Suggest a feature or improvement.** Start a thread in the repository's Discussions tab under "Ideas / RFCs." Describe the problem you're trying to solve, not just the solution you have in mind. If the idea gets traction and scopes into trackable work, a maintainer will convert it to an Issue.

**Fix a bug or implement a feature.** Look for Issues labeled `good first issue` or `help wanted` for vetted entry points. If you want to tackle something larger, open a Discussion or comment on the Issue first so we can align on approach before you invest significant time.

**Improve documentation.** Typos, unclear explanations, missing examples, broken links — all fair game. Documentation PRs are welcome and valued. Our docs build with MkDocs; see individual repo READMEs for build instructions.

**Ask a question.** Use the Discussions tab, not Issues. Questions are welcome. If your question reveals a gap in the docs, that's a contribution too.

## Development workflow

1. **Fork** the repository and create a branch from `main`. Use a descriptive branch name (e.g., `fix/yaml-parsing-error` or `feature/add-csv-export`).

2. **Make your changes.** Keep commits focused. Write commit messages that explain *why*, not just *what*. We appreciate [Conventional Commits](https://www.conventionalcommits.org/) format but do not enforce it.

3. **Test your work.** If the repo has tests, run them and confirm they pass. If you're adding new behavior, add tests for it. If the repo doesn't have a test suite yet, describe how you verified your changes in the PR.

4. **Open a pull request** against `main`. In the PR description, reference any related Issue or Discussion, describe what you changed and why, and note anything a reviewer should pay attention to.

5. **Respond to feedback.** Maintainers may request changes. This is normal and not a judgment on your work — it's how we keep the codebase coherent.

## Code and content standards

**Python projects** — Follow PEP 8. Use type hints where practical. Docstrings on public functions and classes.

**JavaScript/TypeScript projects** — Consistent formatting with the existing codebase. If the repo has a linter config, use it.

**Markdown and documentation** — Write in plain, direct prose. Avoid jargon that isn't defined. Use ATX-style headings (`#`). One sentence per line is preferred for clean diffs.

**Commit messages** — Present tense, imperative mood (e.g., "Fix validation error on empty frontmatter" not "Fixed" or "Fixes"). Keep the subject line under 72 characters.

## What to expect

Maintainers review PRs as time allows. We aim to respond to new Issues and PRs within a week, but response times may vary. If your PR has gone quiet for more than two weeks, a polite ping is welcome.

Not every suggestion or PR will be merged. If we decline a contribution, we'll explain why. Disagreement is fine; we ask only that it stay constructive.

## Community standards

All participants are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md). The short version: be respectful, be constructive, and remember that the people on the other side of the screen are doing this work because they care about it.

## Questions?

If something in this guide is unclear or you're not sure where to start, open a Discussion. We'd rather help you get oriented than have you guess.