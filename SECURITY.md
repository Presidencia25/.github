# Security Policy

## Supported versions

The table below lists which versions of each Presidencia25 project currently receive security patches. Individual repositories may override this policy with their own `SECURITY.md`.

| Status | Support |
|--------|---------|
| ✅ Latest release | Full security support |
| ⚠️ Previous minor | Critical fixes only (90 days) |
| ❌ Older releases | No support |

## Reporting a vulnerability

**Please do not disclose security vulnerabilities through public GitHub issues, pull requests, or discussions.**

Send a detailed report to **seguridad@presidencia.gob.mx** with:

1. A description of the vulnerability and its potential impact
2. The affected repository and version (or commit SHA)
3. Step-by-step instructions to reproduce the issue
4. Any proof-of-concept code, screenshots, or logs (redact personal data)

You will receive an acknowledgement within **2 business days** and a status update within **7 business days**.

## Disclosure timeline

| Day | Action |
|-----|--------|
| 0 | Report received, acknowledgement sent |
| 1–7 | Triage and severity assessment |
| 8–30 | Fix developed and reviewed |
| 31–45 | Fix released and advisory published |
| 90 | Public disclosure (if not already done) |

We follow [coordinated vulnerability disclosure](https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html). If you act in good faith and follow this process we will not pursue legal action against you.

## Scope

All code hosted under the Presidencia25 GitHub organization is in scope, with particular priority given to:

- Citizen-facing apps and APIs
- AI/ML inference services handling personal data
- Authentication and authorisation components
- Data pipelines that process sensitive government information

## Bug bounty

There is currently no monetary bug-bounty programme. We recognise contributors in our release notes and `SECURITY_ACKNOWLEDGEMENTS.md` in each repository.
