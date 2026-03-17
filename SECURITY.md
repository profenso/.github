# Security Policy

## Reporting a Vulnerability

**Do not open a public issue for security vulnerabilities.**

If you discover a security vulnerability in any Profenso repository, please report it privately using GitHub's built-in vulnerability reporting:

1. Go to the affected repository
2. Click the **Security** tab
3. Click **Report a vulnerability**
4. Fill in the details

We will acknowledge your report within 48 hours and provide an initial assessment within 5 business days.

## What we consider a vulnerability

- Exposed secrets, tokens, or credentials
- Authentication or authorisation bypasses
- Injection vulnerabilities (SQL, command, etc.)
- Insecure default configurations that could be exploited
- Dependency vulnerabilities with a known exploit

## What is NOT a vulnerability

- Feature requests or general security improvements — use the **Security Concern** issue template
- Dependabot alerts that have no known exploit — these are tracked and triaged internally

## Security measures

All Profenso repositories enforce:

- Secret scanning with push protection
- Dependabot alerts and security updates
- Pre-commit secret detection (TruffleHog)
- Required code review before merge
- CI security scanning (Trivy, Checkov, Bandit)
