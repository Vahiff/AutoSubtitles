# Security Policy

## Supported Versions

The active `main` branch is the only supported development line unless release branches are created later.

## Reporting A Vulnerability

Do not open public issues for secrets, authentication bugs, payment bugs, data leaks, or anything that could put users at risk.

Report security concerns privately to the repository owner with:

- affected repository and branch
- steps to reproduce
- expected and actual result
- screenshots or logs if safe to share
- suggested fix if known

## Security Rules

- Never commit API keys, passwords, signing keys, payment secrets, or private certificates.
- Keep `.env` files local.
- Treat uploaded audio, video, and subtitles as private user data.
- Delete temporary generated files when they are no longer needed.
