# Web App Security Scanner

Automated OWASP Top 10 vulnerability scanner for web applications with manual verification, exploitation validation, and remediation guidance.

## Features

- Automated Scanning: SQL injection, XSS, CSRF, authentication bypass
- Manual Verification: Proof-of-concept generation and validation
- Sensitivity Analysis: Security header analysis, configuration review
- Remediation Guidance: Fix prioritization and implementation steps
- Report Generation: HTML/PDF with CVSS scores and evidence
- CI/CD Integration: Pipeline-ready scanning

## Quick Start

```bash
git clone https://github.com/Korir555/webapp-security-scanner.git
cd webapp-security-scanner
pip install -r requirements.txt
python scanner.py --url https://target.com --deep
```

## Test Coverage

- SQL Injection (union, time-based, error-based)
- XSS (reflected, stored, DOM-based)
- CSRF token validation
- Authentication/session weaknesses
- Sensitive data exposure
- Security misconfiguration
- File upload vulnerabilities

## Technologies

Python 3.9+ | Requests | BeautifulSoup | Selenium | OWASP ZAP integration

## Hiring Relevance

- Web security testing and penetration testing
- Vulnerability assessment automation
- OWASP Top 10 expertise
- Security scanning operations

## Documentation

Full methodology and sample reports: Case Study

## License

MIT License
