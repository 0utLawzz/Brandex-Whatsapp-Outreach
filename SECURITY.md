# Security Policy

## Reporting a Vulnerability

Please report security issues privately to **net2outlawzz@gmail.com** with the subject `[SECURITY] Customer-Outreach-Suite`.

Include a clear description, steps to reproduce, and potential impact. Do not open public issues for security vulnerabilities.

## Scope notes

- Do not commit production contact lists or CSVs containing client PII.
- Keep `DATABASE_URL` and any future API secrets out of the repository (use `.env`, never commit it).
- This tool is designed for human-confirmed WhatsApp sends via `wa.me` — do not turn it into unattended bulk spam.
