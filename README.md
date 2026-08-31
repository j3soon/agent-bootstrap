# agent-bootstrap

Shared agent instructions and skills for bootstrapping new repositories.

## Usage

In a new repository, ask your agent:

```
Read https://github.com/j3soon/agent-bootstrap and follow its
skills/agent-init to initialize this repository's agent configuration.
```

The skill installs the root `AGENTS.md` as the new repo's base guidelines,
the `artifacts/` convention, and reusable skills.

## Layout

- `AGENTS.md`: base agent guidelines, copied into new repositories.
- `skills/`: reusable skills.
- `artifacts/`: disposable output, ignored by Git.
