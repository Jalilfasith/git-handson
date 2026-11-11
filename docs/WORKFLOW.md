# DevOps Git Workflow

## Branches

- main: Stable release branch
- dev: Integration and testing branch
- feature/*: Task-specific branches

## Feature Development

1. Update the local dev branch.
2. Create a new feature branch from dev.
3. Modify project files.
4. Review changes using git diff.
5. Stage and commit the changes.
6. Check for credentials and other secrets.
7. Push the branch to GitHub.
8. Open a pull request into dev.
9. Resolve review comments and conflicts.
10. Merge approved changes.

## Release Process

1. Confirm that dev is ready.
2. Open a pull request from dev into main.
3. Review and merge.
4. Create an annotated version tag on main.
5. Publish a GitHub release.

## Security Reminder

Never commit real credentials.
Use .gitignore for local configuration files.
Review staged changes and perform secret scanning.
