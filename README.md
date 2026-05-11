<!--
Copyright (c) 2026 Starisian Technologies and AI West Africa.
All rights reserved. Proprietary and confidential.
CONFIDENTIAL · PATENT PENDING
-->

# SPARXSTAR Digital Village Elder — Governance Repository

A governance-aware digital infrastructure framework defining the relationship between AIWA governance systems, Starisian technical infrastructure, and the Digital Village Elder (DVE) operational stack for culturally grounded AI, language preservation, educational publishing, and contributor rights stewardship.

---

## Institutional Architecture

| Layer | Institution | Role |
|---|---|---|
| Governance Authority | AI West Africa (AIWA) | Governance, stewardship, contributor rights, cultural governance, dataset permission authority |
| Infrastructure Authority | Starisian Technologies | Software, infrastructure, AI systems, patents, platform operations |
| Operational Enforcement | Digital Village Elder (DVE) | Governance-integrated operational stack — the bridge between AIWA policy and Starisian infrastructure |
| Platform Foundation | SPARXSTAR | Core platform and infrastructure layer |

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
