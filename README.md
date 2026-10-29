# Agent Skills

A curated set of reusable skills for consistent guidance across AI coding agents and repositories. The original uploaded instructions are preserved; skill identifiers are normalized to match their folder names.

## Install

Install all ten skills to all detected agents in a target repository:

```sh
npx skills add markfoster314/agent-skills --all
```

For a machine-wide install instead of a project-local install, use:

```sh
npx skills add markfoster314/agent-skills --all --global
```

Because this repository is private, the machine running the command needs GitHub access to it.

## Included skills

- `responsive-cross-device-ui` — Make UI responsive across devices
- `secure-ai-features` — Secure AI features against prompt injection
- `validate-and-encode-input` — Validate and encode untrusted input
- `vet-dependencies` — Vet dependencies before adding
- `accessibility-baseline` — Meet an accessibility baseline
- `check-licenses` — Check dependency licenses
- `handle-sensitive-data` — Handle personal and sensitive data
- `instrument-observability` — Instrument observability and graceful errors
- `make-apps-resilient` — Make apps resilient to abuse and overload
- `pre-publish-review` — Review before shipping

## Layout

Each skill lives at `skills/<skill-name>/SKILL.md`, so it can be installed independently by skill-aware agent tooling.
