# Semantics of commits and rules for running a project on git
Description of how to commit.
You can see the original semantics [here](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716).

## Semantics
Commit message template
```
[type]: (Where: what) (small description).


Full description of the commit (optional)
```
- **feat**: New functionality to the codebase.
- **fix**: Fixed a bug in the codebase.
- **style**: Changes related to code formatting, style rules, indentation, etc.
- **docs**: Change any documentation (files and code).
- **refactor**: Rewriting code without changing functionality.
- **test**: Add or correct tests
- **chore**: Changes not in the codebase or documentation.
- **revert**: Reverts the previous commit.
- **rest**: other changes.

## Rules

- One change - one commit.
- detailed description.
- Message Length Limit: ~50 characters for short description.
- Working on branches
- Branches are merged using the flag: **--no-ff**