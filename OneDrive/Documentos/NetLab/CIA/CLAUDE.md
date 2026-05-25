# Claude Code — Project Guidelines

## Git Workflow

- **Never commit directly to `main`.**
- For every task or set of changes, create a feature branch first:
  ```
  git checkout -b feature/short-description
  ```
- Commit changes to the feature branch, push it, then open a PR into `main` via `gh pr create`.
- Branch naming convention: `feature/<topic>`, `fix/<topic>`, `chore/<topic>`.

## Repository

- Remote: https://github.com/KLMontenegro/PrepCourse-Henry-No-Readme
- Default base branch: `main`
- GitHub account: KLMontenegro
