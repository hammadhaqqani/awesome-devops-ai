# Contributing to Awesome DevOps AI

Thank you for contributing! This list is community-driven and we welcome additions that help DevOps engineers discover AI tools.

## Guidelines

### Adding a Tool

1. Make sure the tool is **relevant to DevOps, SRE, or Platform Engineering** with a clear AI/ML component.
2. Check that the tool is **not already listed**.
3. Add the tool to the **appropriate category** in alphabetical order within the category.
4. Use the following format:

```markdown
- [Tool Name](https://url) - One-line description of what it does. `open-source` `tag`
```

For open-source tools on GitHub, include a star badge:

```markdown
- [Tool Name](https://github.com/org/repo) - Description. `open-source` ![Stars](https://img.shields.io/github/stars/org/repo?style=flat)
```

### Description Rules

- Keep descriptions to **one sentence** (aim for under 120 characters).
- Start with a verb or noun, not "A tool that..."
- Be specific about what makes the tool useful for DevOps.
- Do not use marketing language or superlatives.

### Tags

Use these tags where applicable:

| Tag | Meaning |
|-----|---------|
| `open-source` | Source code is publicly available |
| `commercial` | Paid product or service |
| `cncf` | CNCF Sandbox, Incubating, or Graduated project |
| `aws` | AWS-specific or AWS-maintained |
| `github` | GitHub-maintained |
| `cli` | Command-line tool |
| `ide` | IDE extension or plugin |
| `free` | Free to use (not necessarily open-source) |

### New Categories

If you believe a new category is needed:

1. Open an issue first to discuss the category.
2. A new category should have at least 3 tools to justify its existence.
3. Include a one-line description of what the category covers.

### Quality Standards

- Only add tools you have **personally used or thoroughly evaluated**.
- Tools should be **actively maintained** (commit activity within the last 6 months).
- Deprecated or archived projects should not be added.
- Preference is given to open-source tools, but well-known commercial tools are welcome.

## How to Submit

1. Fork this repository.
2. Create a new branch: `git checkout -b add-tool-name`.
3. Make your changes to `README.md`.
4. Commit: `git commit -m "Add ToolName to CategoryName"`.
5. Push: `git push origin add-tool-name`.
6. Open a Pull Request with a brief explanation of why the tool belongs.

## Reporting Issues

- **Broken links**: Open an issue or PR with the fix.
- **Outdated info**: Open an issue with the correct information.
- **Removal requests**: Open an issue explaining why a tool should be removed.

## Code of Conduct

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).
