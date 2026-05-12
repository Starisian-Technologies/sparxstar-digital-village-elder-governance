<!--
Copyright (c) 2026 Starisian Technologies and AI West Africa.
All rights reserved. Proprietary and confidential.
CONFIDENTIAL · PATENT PENDING
-->

# SPARXSTAR Digital Village Elder — Governance Repository

A governance documentation repository for the AIWA–Starisian–DVE ecosystem. Starisian Technologies develops provenance-aware executable governance infrastructure for Works, semantic knowledge systems, and AI-capable computational environments. AIWA is the governance and stewardship authority. DVE enforces AIWA governance rules through the SPARXSTAR executable governance platform.

---

## Institutional Architecture

| Layer | Institution | Role |
|---|---|---|
| Governance Authority | AI West Africa (AIWA) | Governance, stewardship, contributor rights, cultural governance, dataset permission authority |
| Infrastructure Authority | Starisian Technologies | Computational governance and semantic rights infrastructure; provenance-aware systems; SPARXSTAR and DVE operations; patents |
| Operational Enforcement | Digital Village Elder (DVE) | Governance enforcement layer running on SPARXSTAR — bridge between AIWA governance authority and Starisian infrastructure authority |
| Platform Foundation | SPARXSTAR | Executable governance platform: tokenized semantic governance, provenance continuity, computational rights enforcement, attribution preservation, royalty-aware processing of governed Works |

> Starisian Technologies operates the DVE infrastructure environment configured to enforce applicable AIWA governance policies and contributor permissions.

---

## Repository Structure

```
dve/
  framework/          DVE-FRM-01 — Apex governance document
  standards/          DVE-STD-* series
  controls/           DVE-CTRL-* series
  procedures/         DVE-PROC-* series
  registries/         DVE-REG-* series

aiwa/
  constitutional/     AIWA-CONST-* series
  policy/             AIWA-POL-* series
  governance/         AIWA-GOV-* series
  documents/          AIWA-DOC-01, AIWA-DOC-02, AIWA-DOC-03

starisian/
  policy/             STAR-POL-* series

outputs/
  docx/               Auto-generated DOCX (CI/CD)
  pdf/                Auto-generated PDF (CI/CD)

.github/
  workflows/          generate-outputs.yml
  templates/          governance-reference.docx (Pandoc template)
```

---

## CI/CD: Automated Output Generation

Every push to `main` or `develop` triggers `.github/workflows/generate-outputs.yml`, which:

1. Converts all governance markdown documents to DOCX using Pandoc and the Starisian reference template
2. Converts each DOCX to PDF using LibreOffice headless
3. Commits generated files to `outputs/docx/` and `outputs/pdf/`

---

## Licensing

All documents in this repository are the confidential, proprietary work of Starisian Technologies and AI West Africa. No open-source license applies. See `AGENTS.md` for full governance instructions.

*Copyright (c) 2026 Starisian Technologies and AI West Africa. All rights reserved. Proprietary and confidential. CONFIDENTIAL · PATENT PENDING*
