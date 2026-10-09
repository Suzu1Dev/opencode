# opencode

The OpenCode core package: the CLI, server, and core logic.

Requirements: [Bun](https://bun.sh) 1.3+

From the repository root, install dependencies and start OpenCode:

```bash
bun install
bun run dev
```

`bun run dev` runs `bun run --cwd packages/opencode src/index.ts`. To run the entry point directly from this directory:

```bash
bun run src/index.ts
```

Without arguments, both commands start the interactive TUI. To check your setup, pass `--help` or `--version`:

```bash
bun run dev --help             # from the repository root
bun run src/index.ts --version # from packages/opencode
```

See [CONTRIBUTING.md](../../CONTRIBUTING.md) for the full development guide.
