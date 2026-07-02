# Contributing to Codvix Solutions

Welcome! We maintain high code quality standards to ensure our platforms are fast, secure, and maintainable. Please follow these development guidelines:

## Git Branching Strategy
- Main branch: `main` (requires PR approval and passing tests to merge).
- Feature branches: `feature/short-description`
- Bug fix branches: `bugfix/short-description`
- Hotfix branches: `hotfix/short-description`

## Commit Messages
We use descriptive commit messages. Please format your commits as:
- `feat: add WhatsApp webhook endpoint`
- `fix: resolve page layout drift on Safari browser`
- `docs: update setup instructions in README`

## Code Style & Formatting
- **Linting**: Ensure code passes formatting rules (`npm run lint` or `black` for Python) before creating a PR.
- **Testing**: Write unit tests for all new helper functions and endpoints. Aim for a minimum of 80% coverage.
