<!-- agent-layout:map:v1 -->
# Agent guide for SalesSquad/open-design

## Purpose and ownership

This guide covers work in `SalesSquad/open-design`.
Start with the project description in [`README.md`](../../README.md).
Check path ownership in [`.github/CODEOWNERS`](../../.github/CODEOWNERS).

## Source map

- Project contents — [`apps`](../../apps), [`packages`](../../packages), [`templates`](../../templates), [`scripts`](../../scripts), [`tools`](../../tools).
- Project documents — [`CHANGELOG.md`](../../CHANGELOG.md), [`CONTEXT.md`](../../CONTEXT.md), [`MAINTAINERS.md`](../../MAINTAINERS.md).
- Project definition — [`package.json`](../../package.json).
- Verification — [`.github/workflows/agent-pr-explore-sandbox.yml`](../../.github/workflows/agent-pr-explore-sandbox.yml), [`.github/workflows/agent-pr-explore.lock.yml`](../../.github/workflows/agent-pr-explore.lock.yml), [`.github/workflows/autofix.atom.yml`](../../.github/workflows/autofix.atom.yml).
- Local instructions — [`.github/AGENTS.md`](../../.github/AGENTS.md), [`CLAUDE.md`](../../CLAUDE.md), [`apps/AGENTS.md`](../../apps/AGENTS.md), [`packages/AGENTS.md`](../../packages/AGENTS.md).

## Develop and verify

Read [`CONTRIBUTING.md`](../../CONTRIBUTING.md) before selecting a change.
The root [`package.json`](../../package.json) declares `pnpm run typecheck`. Review its implementation and run the relevant check for the change.

## Research and handoff

Check prior issues, pull requests, source material and verified results before repeating work. Keep private inputs with their authorized owner. Record the source revision, result, evidence and remaining limits in the current task or pull request.
<!-- agent-layout:map:end sha256=ccdda3ff38f25855c3633d70c664ecc6cce1f2c2bc0ffd500f7e25d8b6b34616 -->
