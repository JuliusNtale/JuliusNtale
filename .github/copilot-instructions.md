# Copilot / AI Agent Instructions — JuliusNtale

Summary
- This repository currently contains only a top-level README ([README.md](README.md)). There are no detected source directories, build manifests, or test configs.

Primary goal for an AI agent
- Avoid making assumptions about language, frameworks, or build tools. First confirm with the repository owner before scaffolding or adding language-specific files.

What to check (in order)
- Look for repo manifests: `package.json`, `pyproject.toml`, `requirements.txt`, `pom.xml`, `Cargo.toml`.
- Look for sources: `src/`, `app/`, `lib/`, `packages/`, `services/`.
- Look for tests: `tests/`, `spec/`, `__tests__/`.
- Look for CI/workflows: `.github/workflows/`.

If you find manifests or code
- Use the detected language/tooling. Example: if `package.json` exists, run `npm test` locally (or report the test command from `package.json`).
- Preserve existing project layout and naming conventions. Do not move files between folders without the owner's explicit approval.

Repository-specific notes
- Contact and profile information: see [README.md](README.md) for the maintainer email and links. When in doubt about design decisions, ask the maintainer (email provided in README).
- Because this repo currently lacks code, propose changes as drafts/PRs and request confirmation before major scaffolding.

Examples of safe first tasks
- Add a minimal CONTRIBUTING.md or issue template asking which language/framework to prefer.
- Propose a scaffold (e.g., Node, Python) as a separate branch and include a short README describing the choices.

When updating this file
- If you merge this with other agent docs, retain any contact or workflow commands from the originals.

Where to look next
- If you are preparing a code change, search the repository root and common top-level folders for newly added files before proceeding.

Questions to ask the user (before major work)
- Which language or framework should I use for scaffolding?
- Do you want a CI workflow and which runner (GitHub Actions, other)?

Revision log
- 2025-12-29: Initial guidance added (derived from repository state: README only).
