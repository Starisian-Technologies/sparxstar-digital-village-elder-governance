<!--
Copyright (c) 2026 Starisian Technologies and AI West Africa.
All rights reserved. Proprietary and confidential.
CONFIDENTIAL · PATENT PENDING
-->

# Repository Instructions for GitHub Copilot

## What This Repository Is

This repository defines the governance architecture for the AIWA–Starisian–DVE ecosystem. It is not a software project. It is a governance documentation system for a governance-aware digital infrastructure framework covering culturally-grounded AI, educational publishing, language preservation, and contributor-centered dataset stewardship.

Every document in this repository carries institutional weight. Accuracy, institutional separation, and terminological precision are non-negotiable.

---

## Core Institutional Structure

**AI West Africa (AIWA)** is the governance, stewardship, contributor rights, educational publishing, cultural protection, and dataset permission authority. AIWA is a Gambian-led institution operating under the laws of The Republic of The Gambia.

**Starisian Technologies** is an independent software, infrastructure, AI systems, and patent-owning company incorporated in California. Starisian develops and operates the SPARXSTAR platform and the DVE operational stack. Starisian must never be written as merely AIWA's captive technology arm.

**Digital Village Elder (DVE)** is the AIWA-specific governance-integrated operational stack developed and operated by Starisian Technologies. DVE is the environment where AIWA governance policies, contributor permissions, cultural restrictions, provenance requirements, and AI dataset controls are technically implemented and enforced.

**SPARXSTAR** is the core platform and infrastructure layer on which DVE runs. SPARXSTAR is developed and operated by Starisian Technologies.

---

## The Non-Negotiable Rule

**Do not collapse AIWA, Starisian, DVE, and SPARXSTAR into one entity or role.**

| Layer | Role |
|---|---|
| AIWA | Governance, stewardship, contributor rights, cultural governance, dataset permission authority |
| Starisian Technologies | Software, infrastructure, AI systems, patents, platform operations |
| DVE | Governance-integrated operational stack — the bridge between AIWA policy and Starisian infrastructure |
| SPARXSTAR | Core platform and infrastructure layer |

The one-sentence architecture statement is:

> Starisian Technologies operates the DVE infrastructure environment configured to enforce applicable AIWA governance policies and contributor permissions.

This sentence must be your reference whenever describing the AIWA–Starisian–DVE relationship. Use it verbatim or use language consistent with it.

---

## Authority Boundaries

**AIWA decides** whether a use is authorised.
**Starisian decides** how approved processing is implemented safely and reliably.
**DVE enforces** AIWA governance rules through Starisian infrastructure.

These three sentences define the total authority model. No document in this repository may contradict them.

---

## Repository Structure and Document Hierarchy

```
dve/
  framework/
    DVE-FRM-01-digital-village-elder-governance-framework.md   ← APEX DOCUMENT
  standards/
    DVE-STD-*.md
  controls/
    DVE-CTRL-*.md
  procedures/
    DVE-PROC-*.md
  registries/
    DVE-REG-*.md

aiwa/
  constitutional/
    AIWA-CONST-*.md
  policy/
    AIWA-POL-*.md
  governance/
    AIWA-GOV-*.md
  documents/
    AIWA-DOC-01-classification.md
    AIWA-DOC-02-legal-alignment.md
    AIWA-DOC-03-process-and-procedures.md

starisian/
  policy/
    STAR-POL-*.md
```

---

## Policy Architecture

When creating or revising documents, observe the following hierarchy strictly:

### 1. AIWA Constitutional and Policy Layer

Documents in `aiwa/` define AIWA's governance authority. They must:

- Establish AIWA as the governance and stewardship authority (not a platform owner, not a software operator)
- Address: contributor rights, cultural stewardship, rights administration, AI dataset governance, provenance and consent
- Operate under Gambian law as the primary legal framework
- Reference UNESCO frameworks as interpretive support only — not as controlling authority
- Never grant AIWA ownership of Starisian technology or SPARXSTAR platform components
- Never describe AIWA as controlling or directing Starisian's infrastructure decisions

### 2. Starisian Policy Layer

Documents in `starisian/policy/` define Starisian's independent authority. They must:

- Establish Starisian as an independent company (not as AIWA's technology arm)
- Address: corporate governance, software development, AI systems governance, platform security, patent and IP governance, infrastructure operations, governance interoperability
- Operate under California and applicable US law as the primary legal framework
- Never subordinate Starisian's infrastructure authority to AIWA governance decisions

### 3. DVE Framework and Standards Layer

Documents in `dve/` define the DVE operational enforcement environment. They must:

- Reference DVE-FRM-01 as the apex governance document — all DVE documents are subordinate to it
- Describe DVE as the bridge between AIWA governance authority and Starisian infrastructure authority
- Never claim governance authority (that belongs to AIWA)
- Never claim infrastructure design authority (that belongs to Starisian)
- Address: AIWA policy implementation, dataset classification controls, provenance logging, cultural restriction enforcement, contributor permission mapping, AI processing controls, revocation and deletion handling, auditability and traceability

---

## Document Drafting Rules

### Language and Tone

- Use precise institutional governance language throughout
- Avoid generic SaaS language (do not write "users", "features", "the app", "the service")
- Avoid language that suggests AIWA owns Starisian technology or that Starisian owns contributor works or cultural materials
- Write as if this document may be reviewed by: Gambian government officials, international rights organizations (WIPO, UNESCO), investors, legal counsel, and community leaders — because it may be
- Use present tense for governance rules and system behaviour
- Use numbered clauses (1.1.1, 1.1.2) for legal precision
- Avoid hedging language that weakens governance positions ("may wish to", "could consider", "it is suggested that")

### Terminology Precision

Always use these terms consistently:

| Term | Definition |
|---|---|
| Contributor | A person who submits a work to AIWA through an authorized intake channel |
| Work | An intellectual creation fixed in tangible form, submitted to AIWA |
| Folklore | Expression of community cultural heritage with no identifiable individual author, transmitted through generations |
| TCE | Traditional Cultural Expression — protected under Gambian law |
| Governed artifact | A work that has entered the DVE governed pipeline |
| Sieve | The Mḗh₁n̥s governance enforcement gate |
| QUARANTINE | The DVE holding state for payloads that fail governance evaluation — not deletion |
| Release Receipt | The GovernanceToken issued by Mḗh₁n̥s when a payload clears the Sieve |
| ArtifactGovernanceDeclaration | The permanent, immutable governance record attached to every governed artifact |
| Personal Policy Token | The short-lived contributor governance preference instrument minted by Sky Esu at release |
| Group Policy | The standing community governance authority declaration, senior to Personal Policy |

Never use these in AIWA or DVE governance documents:
- "de-identified data" (use "pseudonymized" or "identity-dissociated" with specific definition)
- "user" as a term for community contributors
- "platform" to mean AIWA (SPARXSTAR is the platform; AIWA is the institution)
- "service" to describe AIWA's role (AIWA is a stewardship authority, not a service provider)

---

## Structural Requirements for New Documents

Every new document must include:

```markdown
| Field | Value |
|---|---|
| Document ID | [SERIES]-[TYPE]-[NUMBER]-[short-name] |
| Version | 1.0 |
| Status | Draft / Active / Normative / Superseded |
| Classification | CONFIDENTIAL or CONFIDENTIAL · PATENT PENDING |
| Date | [Month Year] |
| Issuing Authority | [AIWA / Starisian Technologies / Joint] |
| Cross-Reference | [list related documents] |
```

Every AIWA document must close with:

```
End of [DOCUMENT-ID]

*AI West Africa is a Busumbala Born, Gambian Grown Company.*

*Copyright (c) 2026 AI West Africa. All rights reserved.*
```

---

## CI/CD — Output Generation on Every Push

This repository is configured to generate formatted DOCX and PDF outputs on every push to `main` or `develop`.

### GitHub Actions Workflow

The workflow at `.github/workflows/generate-outputs.yml` runs on every push and:

1. Converts all `.md` files in `dve/framework/`, `dve/standards/`, `dve/controls/`, `aiwa/documents/`, and `aiwa/policy/` to DOCX using Pandoc with the configured reference template
2. Converts each DOCX to PDF using LibreOffice headless
3. Commits the generated files to `outputs/docx/` and `outputs/pdf/` with the commit message `[ci] regenerate governance document outputs`
4. Does NOT generate outputs for `README.md`, `AGENTS.md`, or files in `archive/`

### Reference Template

The Pandoc reference template is at `.github/templates/governance-reference.docx`. This template:

- Uses Arial as the primary font
- Uses the AIWA/Starisian green colour palette (primary: #1A4D2E)
- Includes the DVE-FRM-01 header/footer style
- Is maintained by Starisian Technologies and must not be modified without authorization

### Output Naming Convention

Generated outputs use the source file name with the extension changed:

```
dve/framework/DVE-FRM-01-digital-village-elder-governance-framework.md
→ outputs/docx/DVE-FRM-01-digital-village-elder-governance-framework.docx
→ outputs/pdf/DVE-FRM-01-digital-village-elder-governance-framework.pdf
```

---

## Licensing

All documents in this repository are the confidential, proprietary work of Starisian Technologies and AI West Africa. They are governed by the Starisian proprietary license. No MIT license, Apache license, or other open-source license applies to any document in this repository.

**Under no circumstances may Copilot add, suggest, or apply a MIT license, Apache license, or any other open-source license to any file in this repository. If you see a license header that is not the Starisian proprietary license, flag it immediately in a PR comment — do not merge.**

The correct license header for all files is:

```
Copyright (c) 2026 Starisian Technologies and AI West Africa.
All rights reserved. Proprietary and confidential.
CONFIDENTIAL · PATENT PENDING
```

---

## Patent Sensitivity

This repository contains governance architecture that is subject to pending patent protection under:

- **Patent Family C — Multi-Tiered Executable Governance**: Personal Policy Token, ArtifactGovernanceDeclaration, three-tier token resolution, cryptographic governance declarations that travel with artifacts

Do not add technical implementation details, code samples, or claim language to governance documents. Reference patent family concepts by name only. If asked to elaborate on technical implementation of the governance token chain, decline and note that this is patent-sensitive territory.

---

## What Copilot Should Do

- Draft governance document text that maintains institutional separation, uses precise terminology, and applies the authority model correctly
- Flag missing survival clauses, undefined terms, or cross-reference gaps
- Flag any language that collapses AIWA, Starisian, DVE, or SPARXSTAR into a single entity
- Flag any unauthorized license header changes
- Maintain the numbered clause structure (1.1.1, 1.1.2) in legal documents
- Add cross-references between related documents when creating or editing
- Suggest appropriate AIWA document cross-references when new governance rules are introduced

## What Copilot Must Not Do

- Collapse AIWA, Starisian, DVE, and SPARXSTAR into one entity
- Write AIWA as a technology company or platform operator
- Write Starisian as AIWA's subordinate or captive technology arm
- Apply MIT, Apache, or any open-source license to any file
- Add technical implementation details that belong in code, not governance documents
- Use hedging language that weakens governance authority statements
- Generate outputs that describe AIWA as owning Starisian technology
- Generate outputs that describe Starisian as having governance authority over AIWA's classification decisions
