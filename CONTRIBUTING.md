# Contributing to Awesome DevOps AI

Thank you for contributing! This list is community-driven and we welcome additions that help DevOps engineers discover AI tools.

## Guidelines

### Adding a Tool

1. Make sure the tool is **relevant to DevOps, SRE, or Platform Engineering** with a clear AI/ML component.
2. Check that the tool is **not already listed** — duplicate links will fail CI.
3. Add the tool to the **appropriate category** in alphabetical order within the category.
4. Use the following format:

```markdown
- [Tool Name](https://example.com) - One-line description that ends with a period.
```

### Awesome-Lint Rules (CI enforced)

This repo runs [`awesome-lint`](https://github.com/sindresorhus/awesome-lint) on every push and pull request. Your contribution **must pass** these checks. Here are the most common issues:

#### Descriptions must end with proper punctuation

Every list item description **must end with a period** (`.`). Do NOT end descriptions with backtick tags, badges, or other non-punctuation characters.

**Correct:**

```markdown
- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) - AI-powered Kubernetes troubleshooting and diagnostics, a CNCF Sandbox project that scans clusters for issues.
```

**Incorrect (will fail CI):**

```markdown
- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) - AI-powered Kubernetes troubleshooting. `open-source` `cncf`
```

#### No duplicate links

Each URL must appear **exactly once** in the entire README. If a tool fits multiple categories, list it in the **most relevant** category only. The link checker and awesome-lint both flag duplicates.

#### Spelling rules

Awesome-lint enforces specific spellings. Common ones to watch for:

| Incorrect | Correct |
|-----------|---------|
| `K8s` | `Kubernetes` |
| `k8s` | `Kubernetes` |
| `kubernetes` (lowercase) | `Kubernetes` |
| `Postgres` | `PostgreSQL` |
| `postgres` | `PostgreSQL` |
| `Javascript` | `JavaScript` |
| `Typescript` | `TypeScript` |
| `Github` | `GitHub` |
| `Gitlab` | `GitLab` |

#### Table of Contents must match sections

If you add a new section, you **must** also add a corresponding entry in the Table of Contents at the top of the README. Missing ToC entries will fail CI.

### Description Rules

- Keep descriptions to **one sentence** (aim for under 150 characters).
- Descriptions **must end with a period** (`.`).
- Start with a verb or noun, not "A tool that..."
- Be specific about what makes the tool useful for DevOps.
- Do not use marketing language or superlatives.
- Do **not** append inline tags (`` `open-source` `cli` ``) at the end — these break awesome-lint punctuation checks.

### New Categories

If you believe a new category is needed:

1. Open an issue first to discuss the category.
2. A new category should have at least 3 tools to justify its existence.
3. Include a one-line description of what the category covers.
4. Add the new category to the **Table of Contents** — CI will fail without it.

### Quality Standards

- Only add tools you have **personally used or thoroughly evaluated**.
- Tools should be **actively maintained** (commit activity within the last 6 months).
- Deprecated or archived projects should not be added.
- Preference is given to open-source tools, but well-known commercial tools are welcome.
- Links must point to the **canonical URL** — do not use URLs that redirect (e.g., use `github.com/kaito-project/kaito` not `github.com/azure/kaito`).

## How to Submit

1. Fork this repository.
2. Create a new branch: `git checkout -b add-tool-name`.
3. Make your changes to `README.md`.
4. Run `npx awesome-lint` locally to verify your changes pass linting.
5. Commit: `git commit -m "Add ToolName to CategoryName"`.
6. Push: `git push origin add-tool-name`.
7. Open a Pull Request with a brief explanation of why the tool belongs.

### Running CI Locally

Before submitting, you can validate your changes locally:

```bash
# Awesome-lint (format and rules)
npx awesome-lint

# Link check (broken URLs)
npx lychee README.md --verbose --accept 200,204,301,302,403,429
```

Both checks run automatically on your PR. Fix any failures before requesting review.

## Reporting Issues

- **Broken links**: Open an issue or PR with the fix.
- **Outdated info**: Open an issue with the correct information.
- **Removal requests**: Open an issue explaining why a tool should be removed.

## Code of Conduct

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).
