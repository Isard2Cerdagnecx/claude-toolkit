# claude-toolkit

My toolbox of skills for coding agents

Small but I use it weekly.

## Installation

```bash
git clone <this repo>
cp -r skills/* ~/.claude/skills/
```

## Highlights

- Concrete instructions, output formats and examples
- Drop-in compatible with ~/.claude/skills
- YAML frontmatter: name + when-to-use description
- Each skill is a folder with a single SKILL.md
- Versioned like code: review changes in PRs

## How to use

```bash
# skills trigger automatically on matching tasks
# or invoke directly: /code-review
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── skills/
│   ├── code-review/
│   │   └── SKILL.md
│   ├── commit-message/
│   │   └── SKILL.md
│   ├── refactor-plan/
│   │   └── SKILL.md
│   └── test-writer/
│       └── SKILL.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
└── SECURITY.md
```

## License

MIT licensed, see LICENSE.
