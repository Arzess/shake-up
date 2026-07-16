# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| latest  | :white_check_mark: |
| older   | :x:                 |

## Reporting a Vulnerability

If you discover a security vulnerability in ShakeUp, please **do not**
open a public GitHub issue.

Instead, report it privately via [GitHub Security Advisories](../../security/advisories/new)
or email <arsenii.malyshko@gmail.com>.

Please include:
- A description of the vulnerability and its potential impact
- Steps to reproduce
- Any relevant logs, screenshots, or proof-of-concept code

We aim to acknowledge reports within 5 business days and will keep
you updated as we investigate and address the issue.

## Scope

ShakeUp is a local-first mobile app. Notable areas of interest for
security reports include:
- The nutrition data pipeline and asset CDN (integrity of downloaded
  content)
- Any local data storage handling
- Third-party dependencies (see `package.json`)

ShakeUp does not collect or transmit personal user data to any server
we control, so account/auth-related reports are out of scope unless
that changes in a future release.