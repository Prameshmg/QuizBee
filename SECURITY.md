# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in QuizBee, please report it responsibly.

### How to Report

- Open a GitHub issue with the label `security`
- Or contact the maintainer directly

### What to Include

- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

## Security Best Practices

When deploying QuizBee:

- **Change the JWT secret** in production (`JWT_SECRET` in `.env`)
- **Use HTTPS** in production environments
- **Keep dependencies updated** by running `npm audit` regularly
- **Do not expose** the MongoDB URI publicly
- **Use strong passwords** for all user accounts

## Supported Versions

| Version | Supported |
|---------|-----------|
| 1.x     | ✅        |
