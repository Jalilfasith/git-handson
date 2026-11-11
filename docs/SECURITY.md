# Repository Security Checklist

Before each commit or push:

1. Review git status.
2. Check staged changes with git diff --staged.
3. Ensure .env and credential files are ignored.
4. Run secret scanning when a scanner is available.
5. Never commit passwords, API keys or private keys.
6. If a real secret is exposed, revoke or rotate it.
