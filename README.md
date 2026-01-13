# appsec_article playground

This repo vendors an intentionally vulnerable app so you can iterate on GitHub Actions security workflows and compare tool output.

## Included vulnerable project

- OWASP NodeGoat: `vulnerable/nodegoat/`

## Security workflows

The starter workflow lives at `.github/workflows/security.yml` and runs:

- Semgrep (SAST)
- OSV-Scanner (dependency vulnerabilities)
- Trivy (filesystem dependency + OS package scan)

Do not deploy the included app to any environment you care about.
