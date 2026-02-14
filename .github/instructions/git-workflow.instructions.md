---
description: 'Git branching and commit workflow for implementation tasks'
applyTo: '**/*.ts,**/*.js,**/*.py,**/*.go,**/*.ps1,**/*.sql,**/*.vue,**/*.css'
---

# Git Workflow Instructions

When implementing code features or tasks, follow this standardized git workflow to maintain clean, traceable history and organized collaboration.

## Workflow sequence

### 1. Branch creation

When starting work on a new feature or task, create a feature branch from `main`:

```bash
git checkout main
git pull origin main
git checkout -b feature/brief-feature-description
```

Branch naming conventions:
- Use lowercase with hyphens for separators
- Prefix with feature type: feature/, fix/, docs/, refactor/
- Keep names concise and descriptive (e.g., feature/user-auth, fix/cache-bug)
- Never commit directly to main

### 2. Implement feature/task
Develop the requested feature or complete the assigned task, making logical, focused changes.

### 3. Commit work after each logical unit
After implementing each distinct feature, component, function, or group of related changes, commit your work using conventional commits:

```bash
git add <relevant files>
git commit -m "type(scope): description"
```

Commit guidelines:
- Use the git-commit skill to generate appropriate commit messages
- One logical change per commit
- Follow the format: <type>[optional scope]: <description>
- Valid types: feat, fix, docs, style, refactor, perf, test, build, ci, chore, revert
- Keep descriptions under 72 characters, using present tense and imperative mood

### 4. Examples of commit points
Commit after completing:

- A new function or method implementation
- A bug fix
- A component/module addition
- Documentation updates
- Refactoring a section of code
- Adding tests

Multiple small, focused commits are preferred over one large commit.

### 5. Final steps
Once all features/tasks are complete:

- Push your feature branch to the repository
- Create a pull request with a clear description of the changes
- Reference related issues (e.g., "Closes #123")

## Avoiding common issues
Never use --force or --force-with-lease unless explicitly requested
Never commit secrets (.env files, API keys, credentials)
Never skip pre-commit hooks unless explicitly requested
Always push to feature branches, never directly to main
Keep commits logical and related - avoid mixing unrelated changes

##References
Conventional Commits
Git branching model
Git-commit skill documentation