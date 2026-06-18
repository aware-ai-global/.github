# .github

This repository holds organisation-level GitHub configuration for the `aware-ai-global` organisation. A repository named `.github` is a special GitHub repository: files placed here act as defaults for every repository in the organisation that does not provide its own equivalent.

## What it is

Typical contents of an org `.github` repository include:

- A `profile/README.md` that renders on the organisation's public profile page.
- Default community health files such as `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, and issue/pull request templates.
- Shared workflow or `dependabot` defaults.

> Note: the supplied file tree for this repository was empty, so the exact contents could not be confirmed. Update this README once the actual files are added.

## How to use it

This repository is not run as an application. To make changes:

1. Add or edit the relevant configuration file (for example `profile/README.md` for the org profile).
2. Open a pull request against the `main` branch.
3. Once merged, GitHub applies the defaults automatically across the organisation.

## Status

Proof of concept / experimental. Contents are not yet documented because no source files were detected. The owner is set to a placeholder pending review.
