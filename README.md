# SIEM Detection Rules

Professional OWASP Top 10 based detection rules for Splunk and QRadar.

## Structure
- `splunk/` — 15 Splunk detection rules (SPL format)
- `qradar/` — 10 QRadar detection rules (XML format)

## Coverage
| Rule | Attack Type | Platform |
|------|-------------|----------|
| A01 | Broken Access Control | Splunk, QRadar |
| A02 | Cryptographic Failures | Splunk |
| A03 | SQL Injection | Splunk, QRadar |
| A04 | Path Traversal | Splunk, QRadar |
| A05 | Security Misconfiguration | Splunk, QRadar |
| A06 | Vulnerable Components (Log4j) | Splunk, QRadar |
| A07 | Auth Failure / Brute Force | Splunk, QRadar |
| A08 | Integrity Failure | Splunk |
| A09 | Log Injection | Splunk |
| A10 | SSRF | Splunk, QRadar |
| A11 | Mass Scanning | Splunk |
| A12 | Command Injection | Splunk |
| A13 | XSS Attempt | Splunk |
| A14 | XXE Injection | Splunk |
| A15 | Credential Stuffing | Splunk |

## Usage
Rules are deployed via API to Splunk and QRadar automatically.

## Author
aqsin1337
\\
