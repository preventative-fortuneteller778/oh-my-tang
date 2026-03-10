# Contributing

Thanks for helping improve `oh-my-tang-dynasty`.

## Before you open a PR

- Search existing issues and pull requests first.
- Keep changes small, reviewable, and reversible.
- Avoid adding new dependencies unless they are clearly necessary.
- Do not commit local planning/state artifacts such as `.omx/`, `docs/plans/`, or private workspace files.

## Development checklist

Run the release baseline before asking for review:

```bash
bun run ci
```

This runs:

- `bun run typecheck`
- `bun test`
- `bun run build`

## Pull request guidance

- Explain the problem being solved.
- Summarize the behavioral change.
- Note any config, migration, or documentation impact.
- Include verification evidence when possible.

## Code style

- Prefer small diffs over broad refactors.
- Reuse existing patterns before introducing new abstractions.
- Keep operator-facing behavior observable and documented.

## Reporting bugs

Please open an issue with:

- what you expected
- what actually happened
- reproduction steps
- environment details when relevant

For security-sensitive issues, follow [`SECURITY.md`](./SECURITY.md).
