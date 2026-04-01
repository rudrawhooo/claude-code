# src

Community-maintained, TypeScript-based CLI codebase inspired by modern AI coding assistants.

This repository is intended to be fully open for community collaboration.

## Project status

- Status: early open-source release
- Focus: make the code easy to run, review, and improve in public
- Contributions: welcome

## Important notice

This is an independent community project. It is not affiliated with, endorsed by, or maintained by Anthropic.

Contributors must not add proprietary code, leaked assets, private prompts, or any content copied from closed-source products.

## Repository layout

Top-level areas include:

- `commands/`: CLI command implementations
- `services/`: API, analytics, MCP, and runtime service layers
- `tools/`: tool integrations and execution helpers
- `bridge/`, `remote/`: remote and bridge communication modules
- `ink/`, `components/`, `screens/`: terminal UI and rendering logic
- `utils/`: shared infrastructure and helpers

## Getting started

The repository currently does not include a checked-in `package.json` or lockfile at root, so setup depends on how you plan to build/run the code.

Suggested bootstrap flow:

1. Install prerequisites:
   - Node.js 18+
   - Bun (optional, but some imports reference Bun features)
   - Git
2. Clone and enter the repository.
3. Add or restore your project manifest (`package.json`) and dependency lockfile if you maintain them separately.
4. Install dependencies and run your preferred build/test workflow.

Example (adapt to your setup):

```bash
# if you use npm
npm install
npm run build
npm test

# or with bun
bun install
bun test
```

## Open-source workflow

1. Create a feature branch.
2. Make focused changes with tests/docs.
3. Open a pull request with clear rationale and validation steps.
4. Address review feedback and keep commits clean.

See:

- `CONTRIBUTING.md` for contribution rules
- `CODE_OF_CONDUCT.md` for community standards
- `SECURITY.md` for responsible disclosure

## License

Licensed under the MIT License. See `LICENSE`.
