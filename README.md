# Arthais Lottery -- Licenses & Compliance

This repository defines the **licensing foundation, compliance
standards, and automation tooling** for the Arthais Lottery ecosystem.

It provides **canonical license templates**, **configuration schemas**,
and **automation scripts** used to ensure that all Arthais Lottery
repositories --- across multiple languages and execution environments
--- remain legally consistent, auditable, and compliant.

> **Scope:** This repository does **not** contain application code. It
> exists solely to standardize legal and licensing governance across the
> Arthais Lottery platform.

------------------------------------------------------------------------

## 🎯 Purpose

The Arthais Lottery platform is composed of many independent
repositories, including:

-   On-chain smart contracts\
-   Off-chain microservices\
-   Infrastructure-as-Code\
-   Analytics and fraud detection systems\
-   SDKs and shared libraries in multiple languages

This repository ensures that:

-   Every module uses an **approved license**
-   License texts remain **consistent and version-controlled**
-   License generation is **automated and reproducible**
-   Compliance checks can be **validated in CI/CD**

------------------------------------------------------------------------

## 📁 Repository Structure

``` text
arthais-lottery-licenses/
│
├── README.md
├── LICENSE
├── .gitignore
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
│
├── templates/
│   ├── bsl.template
│   └── apache.template
│
├── scripts/
│   └── generate_license.py
│
├── examples/
│   └── license.config.example.json
│
├── docs/
│   ├── architecture.md
│   └── usage.md
│
└── .github/
    ├── workflows/
    │   └── validate-templates.yml
    └── ISSUE_TEMPLATE/
        ├── bug_report.md
        └── feature_request.md
```

------------------------------------------------------------------------

## 📜 Supported License Models

  -----------------------------------------------------------------------
  License                Typical Usage
  ---------------------- ------------------------------------------------
  **Apache License 2.0** SDKs, shared libraries, infrastructure tooling

  **MIT License**        Services, adapters, and internal tooling

  **Business Source      Sensitive financial logic, protocol components
  License (BSL)**        
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## ⚙️ License Automation

``` bash
python scripts/generate_license.py   --config examples/license.config.example.json   --output ../target-repo/LICENSE
```

------------------------------------------------------------------------

## 🧱 Architectural Principles

-   Single Source of Truth\
-   Language-Agnostic\
-   Automation First\
-   Audit-Friendly

------------------------------------------------------------------------

## 🤝 Contributing

See `CONTRIBUTING.md`.

------------------------------------------------------------------------

## 📄 License

Apache License 2.0.
