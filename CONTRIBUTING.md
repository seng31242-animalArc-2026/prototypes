# Contributing

## Branching Strategy

Use short-lived feature branches from the main branch.

- `main` should remain stable and ready to review or release.
- Create branches using a descriptive prefix, such as `feature/`, `fix/`, `docs/`, or `chore/`.
- Open a pull request before merging changes into `main`.
- Keep pull requests focused on one logical change whenever possible.

Example branch names:

```text
feature/add-project-setup
fix/update-readme-links
docs/contributing-guidelines
chore/cleanup-config
```

## Commit Convention

Use clear, present-tense commit messages. Prefer a lightweight conventional commit format:

```text
type: short description
```

Common commit types:

- `feat`: adds a new feature
- `fix`: fixes a bug
- `docs`: changes documentation
- `style`: changes formatting without changing behavior
- `refactor`: changes code structure without changing behavior
- `test`: adds or updates tests
- `chore`: updates maintenance tasks or tooling

Examples:

```text
docs: add initial repository documentation
chore: add starter gitignore
feat: add prototype page
```

## Pull Requests

- Describe what changed and why.
- Include testing or verification notes when applicable.
- Request review before merging.
- Resolve comments before merging.

