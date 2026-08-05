# Security Policy

Mosticare takes the security of its software, data, and customers seriously. This document describes how to report security vulnerabilities responsibly across the entire `Mosticare` GitHub organization.

## Reporting a vulnerability

If you believe you've found a security vulnerability in any Mosticare repository, infrastructure, or service (mosticare.org, the operations dashboard at ops.mosticare.org, the Paperclip agent runtime, the publishing pipeline, or any code in this organization), **please do not open a public GitHub issue.**

Two ways to report. Pick whichever is easier:

1. **GitHub Private Vulnerability Reporting** (preferred): go to the affected repo, click the **Security** tab → **Report a vulnerability**. This routes directly to maintainers with full audit trail.

2. **Email**: send a report to **contact@mosticare.org** with `SECURITY:` in the subject line.

In your report, include:

- A clear description of the vulnerability
- Steps to reproduce, with any required prerequisites
- Affected version, commit SHA, or URL if applicable
- Your assessment of impact and severity
- Whether you've notified anyone else

You'll receive an acknowledgement within **72 hours** and a substantive status update within **7 days**. We're a small team; thank you for your patience.

## Scope

**In scope:**

- mosticare.org and all subdomains (including ops.mosticare.org)
- All repositories in the `Mosticare` GitHub organization
- Paperclip agent runtime endpoints exposed to the public internet
- Customer-data handling pathways (checkout, contact forms, the publishing pipeline)

**Out of scope** (please don't report these):

- Social engineering of Mosticare staff, contractors, or agents
- Physical attacks against Mosticare infrastructure or premises
- Vulnerabilities in third-party dependencies that are not specific to our deployment (please report upstream)
- Findings from automated scanners without a proof-of-concept exploit
- Best-practice violations without demonstrated security impact (e.g., missing HTTP headers, weak TLS ciphers on already-protected endpoints). Feel free to mention them, but they're not bounty-worthy
- Denial-of-service or volumetric attacks
- Issues requiring an attacker to already have physical or administrative access to a Mosticare-owned device

## Safe harbor

Mosticare will not pursue legal action against security researchers who:

- Make a good-faith effort to avoid privacy violations, data destruction, and service interruption
- Test only against accounts and systems they own or have explicit permission to access
- Report vulnerabilities promptly via the channels above
- Don't publicly disclose the vulnerability before we've had a reasonable chance to fix it (typically 90 days, sooner if mutually agreed)
- Don't access, modify, or destroy data that doesn't belong to them

We commit to working with you in good faith and credit you in our disclosure if you'd like.

## Acknowledgements

We're happy to publicly acknowledge researchers who responsibly disclose vulnerabilities, with your consent. Mention this in your report if you'd like to be credited.

---

*Mosticare is two entities: the Mosticare Foundation (non-profit, [mosticare.org](https://mosticare.org)) and Mosticare OÜ (storefront, [mosticare.com](https://www.mosticare.com)). Security contact: contact@mosticare.org.*
