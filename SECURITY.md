# Security Policy

## Scope

This repository is for coursework files and analysis artifacts. It should not contain API keys, passwords, tokens, or other credentials.

## Reporting

If you find sensitive data committed to this repository:

1. Do not reuse or share the exposed data.
2. Remove the secret from the repository and Git history.
3. Rotate the exposed credential in the source system immediately.

## Repository Hygiene

- Keep `.env` files and private keys out of version control.
- Review notebook outputs before committing if they may contain local paths, tokens, or personal data.
- Prefer private repositories when coursework should not be published broadly.
