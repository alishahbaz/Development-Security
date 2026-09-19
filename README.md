# Development Security Wiki

Practical, easy-to-understand guidance for securing your software development lifecycle.

This wiki covers:

- Source code integrity controls
- DevOps toolchain access management
- Software supply chain protection
- Compliance evidence requirements
- Exception handling


---

## Page Map

```mermaid
flowchart TD
    HOME[Home] --> A[Safeguard Source Code Integrity]
    HOME --> B[DevOps Toolchain Access Control]
    HOME --> C[Supply Chain Malware Scanning]
    HOME --> D[Compliance and Evidence]
    HOME --> E[Exception Process]
    HOME --> F[Glossary]

    A --> A1[Branch Protection]
    A --> A2[Pull Requests Review]
    A --> A3[Version Control]
    A --> A4[Commit Signing]
    A --> A5[Archive Repositories]
    A --> A6[Access and Credential Management]

    B --> B1[MFA and SBOM]
    B --> B2[Required Documentation]
    B --> B3[Access Hygiene and Re-assessment]

    C --> C1[Malware Threat]
    C --> C2[Pipeline Scanning]

    D --> D1[Done Criteria]
    D --> D2[Test and Validation]
    D --> D3[Evidence Upload]
```

---

## Quick Links

| Page | Purpose |
|------|---------|
| [Safeguard Source Code Integrity](Safeguard-Source-Code-Integrity) | Branch protection, PR review, credentials |
| [DevOps Toolchain Access Control](DevOps-Toolchain-Access-Control) | Tool access, SBOM, MFA, re-assessment |
| [Supply Chain Malware Scanning](Software-Supply-Chain-Malware-Scanning) | Pipeline malware scanning |
| [Compliance and Evidence](Compliance-and-Evidence) | Done criteria, validation, Sirius upload |
| [Exception Process](Exception-Process) | Non-compliance examples and process |
| [Glossary](Glossary) | Key terms explained |

---
