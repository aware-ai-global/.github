# Organisation `.github`

## What it is

This is the special `.github` repository for the `aware-ai-global` GitHub organisation. GitHub uses this repository to supply default community health files (for example issue templates, pull request templates, contributing guidelines, and the organisation profile README) to any repository in the organisation that does not provide its own.

No source tree, manifest, or entrypoint was detected, so this repository currently holds only GitHub configuration and template files rather than runnable code.

## How it works

GitHub automatically applies files placed here as fallbacks across the organisation. Common locations include:

- `profile/README.md` — shown on the organisation's public profile page.
- `.github/ISSUE_TEMPLATE/` — default issue templates.
- `.github/PULL_REQUEST_TEMPLATE.md` — default pull request template.
- `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md` — default community health files.

## Quickstart

There is nothing to build or run. To change organisation defaults:

1. Clone the repository.
2. Add or edit the relevant template/health file in the expected path.
3. Open a pull request against `main`.

Once merged, the changes apply across organisation repositories that lack their own equivalents.

## Status

Experimental / proof of concept. The repository tree supplied was empty, so the exact set of present files could not be confirmed. Update this README once the actual contents are known.
