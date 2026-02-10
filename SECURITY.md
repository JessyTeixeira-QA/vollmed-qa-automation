# Security Policy

## Supported Versions

We actively provide security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |
| < 1.0.0 | :x:                |

## Reporting a Vulnerability

We take the security of this project seriously. If you believe you have found a security vulnerability, please do not open a public issue. Instead, follow these steps:

1.  **Private Disclosure:** Send a detailed report of the vulnerability to the maintainer.
2.  **Information to Include:**
    *   Description of the vulnerability.
    *   Steps to reproduce.
    *   Potential impact.
3.  **Response Time:** You can expect an acknowledgment within 48 hours. We will provide a timeline for a fix after the initial evaluation.

## Best Practices in this Repository

*   **No Secrets in Code:** Never commit credentials, tokens, or private keys. Use `cypress.env.json` (locally) and environment variables in CI/CD.
*   **Dependency Audits:** We regularly run `npm audit` to identify and patch vulnerable packages.
*   **Minimal Permissions:** Run tests with the minimum necessary access rights.
