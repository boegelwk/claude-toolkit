# claude-toolkit

My toolbox of skills for coding agents

## How to use

```bash
# skills trigger automatically on matching tasks
# or invoke directly: /code-review
```

## Highlights

- Concrete instructions, output formats and examples
- Drop-in compatible with ~/.claude/skills
- YAML frontmatter: name + when-to-use description
- Each skill is a folder with a single SKILL.md
- Versioned like code: review changes in PRs

## Install

```bash
git clone <this repo>
cp -r skills/* ~/.claude/skills/
```

## Project structure

```text
├── docs/
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── skills/
│   ├── code-review/
│   │   └── SKILL.md
│   ├── commit-message/
│   │   └── SKILL.md
│   ├── refactor-plan/
│   │   └── SKILL.md
│   └── test-writer/
│       └── SKILL.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
└── SECURITY.md
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version
