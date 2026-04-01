# Claude Code 

This repository is a community-maintained, open-source reconstruction effort around a TypeScript CLI codebase in the Claude Code ecosystem.

## Why this exists

In 2026, public reporting described an npm packaging incident that exposed source-map artifacts for Claude Code builds. This project exists to study architecture patterns, improve tooling quality in the open, and support collaborative learning.

## Project goals

- Maintain a transparent, contributor-friendly codebase
- Improve reliability, developer experience, and documentation
- Enable public discussion of architecture and implementation tradeoffs
- Build an active contributor community around open development

## Legal and ethical boundaries

This is an independent community project and is not affiliated with, endorsed by, or maintained by Anthropic.

To keep this repository responsibly open-source:

- Do not add proprietary, leaked, confidential, or private material
- Do not submit copied closed-source code
- Contribute only code/content you have rights to publish
- Prefer clean-room implementations and public documentation references

If a maintainer identifies questionable provenance, the change may be removed.

## Repository layout

Top-level areas include:

- `commands/`: CLI command implementations
- `services/`: API, analytics, MCP, and runtime service layers
- `tools/`: tool integrations and execution helpers
- `bridge/`, `remote/`: remote and bridge communication modules
- `ink/`, `components/`, `screens/`: terminal UI and rendering logic
- `utils/`: shared infrastructure and helpers

## Getting started

The repository currently does not include a root `package.json` or lockfile, so setup depends on your local build strategy.

Suggested bootstrap flow:

1. Install prerequisites:
   - Node.js 18+
   - Bun (some modules reference Bun features)
   - Git
2. Clone and enter the repository.
3. Add or restore your project manifest and lockfile if you maintain them separately.
4. Install dependencies and run your local build/test workflow.

Example (adapt to your setup):

```bash
# npm
npm install
npm run build
npm test

# bun
bun install
bun test
```

## Contributing

We welcome improvements to architecture, docs, tooling, quality, and tests.

Before opening a PR:

1. Create a focused branch.
2. Make scoped changes with clear rationale.
3. Include validation notes or tests.
4. Update docs for user-facing behavior changes.

See:

- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`
- `SECURITY.md`

## License

MIT License. See `LICENSE`.
