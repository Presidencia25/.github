# Contributing to Presidencia25 projects

Thank you for helping improve civic technology and public services! This guide applies to all repositories in the **Presidencia25** organization.

## Code of Conduct

All contributors must follow our [Code of Conduct](CODE_OF_CONDUCT.md). By participating you agree to uphold these standards.

## How to contribute

### 1. Find or create an issue

- Browse open issues labelled [`good first issue`](../../issues?q=label%3A%22good+first+issue%22) or [`help wanted`](../../issues?q=label%3A%22help+wanted%22).
- If no issue exists for your idea, open one first and wait for maintainer feedback before writing code.

### 2. Fork and branch

```bash
# Fork via the GitHub UI, then:
git clone https://github.com/<your-username>/<repo>.git
cd <repo>
git checkout -b feat/short-description
```

Use the following prefixes:

| Prefix | Use for |
|--------|---------|
| `feat/` | New features |
| `fix/` | Bug fixes |
| `docs/` | Documentation only |
| `chore/` | Maintenance / tooling |
| `ai/` | Machine-learning or data changes |

### 3. Write code

- Follow the language-specific style guide in the repository (e.g., PEP 8 for Python, Prettier for JavaScript/TypeScript).
- Write or update tests for every changed behaviour.
- Keep commits small and descriptive (`git commit -m "feat: add citizen feedback endpoint"`).

### 4. Open a pull request

- Fill in the pull-request template completely.
- Link the related issue with `Closes #<issue-number>`.
- Request at least one reviewer from the `@Presidencia25/maintainers` team.

### 5. Review process

- Maintainers aim to review within **5 business days**.
- Address all requested changes before the PR can be merged.
- All CI checks must pass.

## Reporting security vulnerabilities

Please **do not** open a public issue for security vulnerabilities. Follow the process in [SECURITY.md](SECURITY.md).

## Questions?

Open a [Discussion](../../discussions) or read [SUPPORT.md](SUPPORT.md).
