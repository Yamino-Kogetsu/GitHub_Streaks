# GitHub Streak Stats

Automatically generates a **GitHub Streak Stats** SVG every day using GitHub Actions and the excellent project by [DenverCoder1](https://github.com/DenverCoder1/github-readme-streak-stats).

## Preview

![GitHub Streak](./profile/streak.svg)

## Features

- 📅 Automatically updates every day at **00:00 (UTC+7)**
- 🔄 Manual execution via **workflow_dispatch**
- 🔒 Supports **Private Contributions** (using a Personal Access Token)
- 💾 Stores the generated SVG directly in this repository
- ⚡ No external hosting required

## Workflow

The workflow:

1. Runs on schedule or manually.
2. Generates a new streak SVG.
3. Commits the updated image if it has changed.

## Repository Structure

```text
.
├── .github
│   └── workflows
│       └── streak.yml
├── profile
│   └── streak.svg
└── README.md
```

## Credits

- Original project: https://github.com/DenverCoder1/github-readme-streak-stats
- Powered by GitHub Actions

## License

This repository only contains automation workflows.

All credit for the streak card generator belongs to the original project author.