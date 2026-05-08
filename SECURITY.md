# Security Policy

## Supported Versions

| Version | Supported |
|---|---|
| 2.2.x | ✅ Active |
| 2.1.x | ⚠️ Security fixes only |
| < 2.1 | ❌ Not supported |

## Reporting a Vulnerability

Please **do not** open a public GitHub issue for security vulnerabilities.

Report privately to: **francesco@studio1informatica.it**

Include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

Response within: **48 hours** for acknowledgment, **7 days** for assessment.

## False Positives

WinFast Pro X modifies registry keys, runs system commands and writes to HKLM.
These capabilities may trigger antivirus heuristics — they are intentional and required
for the software to function. They are not security vulnerabilities.

If your security software flags the installer, you can verify the SHA-256 hash
published on the Releases page.
