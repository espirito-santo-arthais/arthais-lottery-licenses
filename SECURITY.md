# Security Policy

## Overview

The **Arthais Lottery** ecosystem includes smart contracts, backend
services, infrastructure components, and automation tooling.\
Security is a **top priority**, especially due to the financial,
cryptographic, and decentralized nature of the platform.

This document describes how to report security vulnerabilities
responsibly and how they are handled.

------------------------------------------------------------------------

## 🚨 Reporting a Vulnerability

**Do NOT report security vulnerabilities through public GitHub issues,
pull requests, or discussions.**

If you discover a potential security issue, please follow responsible
disclosure practices.

### How to Report

Please report vulnerabilities by contacting the project maintainers
**privately** using one of the following methods:

-   Direct contact with repository maintainers
-   Encrypted communication when possible
-   Clear and detailed description of the issue

Your report should include:

-   A description of the vulnerability
-   Steps to reproduce the issue (if applicable)
-   Affected components or repositories
-   Potential impact and risk assessment
-   Any suggested mitigations or fixes (optional)

------------------------------------------------------------------------

## 🔐 Scope of Security Issues

Security issues may include, but are not limited to:

### On-chain / Smart Contracts

-   Reentrancy vulnerabilities
-   Integer overflows or underflows
-   Access control flaws
-   Oracle manipulation
-   Economic or incentive exploits

### Off-chain Services

-   Authentication or authorization flaws
-   Data leakage or privacy issues
-   Injection vulnerabilities
-   Misconfigured infrastructure
-   Insecure cryptographic usage

### Infrastructure & Automation

-   CI/CD pipeline compromises
-   Secrets exposure
-   Dependency supply-chain attacks
-   Cloud or container misconfigurations

------------------------------------------------------------------------

## 🛠️ Response Process

Once a security report is received:

1.  Maintainers will acknowledge receipt of the report
2.  The issue will be evaluated and triaged
3.  A fix or mitigation plan will be developed
4.  A patch will be released when ready
5.  Public disclosure will occur **after** remediation, when appropriate

The timeline depends on the severity and complexity of the issue.

------------------------------------------------------------------------

## 🤝 Coordinated Disclosure

We strongly encourage **coordinated disclosure**.

Please allow maintainers reasonable time to investigate and remediate
the issue before any public disclosure.

Unauthorized public disclosure of vulnerabilities may result in loss of
contributor privileges.

------------------------------------------------------------------------

## 🏆 Recognition

At this time, the project does not operate a formal bug bounty program.

However, responsible security researchers may be acknowledged in release
notes or documentation at the discretion of the maintainers.

------------------------------------------------------------------------

## ⚖️ Legal Safe Harbor

We consider security research conducted in good faith, following this
policy, to be authorized.

We will not pursue legal action against researchers who:

-   Follow responsible disclosure
-   Avoid privacy violations
-   Do not exploit vulnerabilities beyond proof-of-concept
-   Do not disrupt production systems

------------------------------------------------------------------------

## 📌 Final Notes

Security is a shared responsibility.

If you are unsure whether an issue is security-related, **err on the
side of caution and report it privately**.

Thank you for helping keep the Arthais Lottery ecosystem secure.
