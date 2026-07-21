# Git and text conventions

This document outlines the standard text conventions for managing code changes, commits, and branches in this repository. Adhering to these rules ensures a clean, readable, and searchable project history.

## 1. Commit messages
We follow the **Conventional Commits** specification. Commit titles must be structured as follows:

### Allowed types
* **feat**: A new feature for the user (e.g., `feat(auth): add Google OAuth login`)
* **fix**: A bug fix for the user (e.g., `fix(api): resolve timeout error on checkout`)
* **docs**: Documentation-only changes (e.g., `docs: update setup instructions in README`)
* **style**: Formatting, missing semi-colons, etc.; no production code change
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **test**: Adding missing tests or correcting existing tests
* **chore**: Updating build tasks, package manager dependencies, etc.

### Formatting rules
* **Case**: Use lowercase for the description.
* **Tense**: Write the description in the imperative, present tense (e.g., "add feature" not "added feature").
* **Length**: Keep the subject line under 50 characters.
* **Punctuation**: Do not end the subject line with a period.

---

## 2. Branch naming
Branches must be lowercase, use hyphens as word separators, and start with the appropriate category prefix:

* **feature/**: For new features (e.g., `feature/user-profile-page`)
* **bugfix/**: For fixing bugs (e.g., `bugfix/broken-submit-button`)
* **hotfix/**: For urgent production fixes (e.g., `hotfix/payment-gateway-crash`)
* **chore/**: For routine tasks and maintenance (e.g., `chore/upgrade-node-version`)

---

## 3. Pull requests
When creating a pull request (PR) to merge into `main`, format the PR title exactly like a commit message (e.g., `feat(ui): implement dark mode toggle`). 

Every PR description should include:
1. **Context**: What problem does this PR solve?
2. **Changes**: A brief bulleted list of what was modified.
3. **Issue Link**: Reference the issue number it closes (e.g., `Closes #124`).
