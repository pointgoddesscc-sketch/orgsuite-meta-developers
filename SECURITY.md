# Security Policy

## Scope
This repository is a public companion site and App Review checklist for OrgSuite / PSE Management.

It does **not** store:
- Meta App Secret
- Facebook passwords
- access tokens
- webhook verify tokens
- private keys or developer certificates

## Secrets
If a Meta App is created, store credentials only in Vercel environment variables or the host keychain.
Never commit `.env` files with live values.

## Reporting
Report suspected credential leaks to the OrgSuite workplace owner (`pointgoddesscc@gmail.com`) and rotate the secret in the Meta App Dashboard immediately.
