<!--
Copyright (c) 2026 Starisian Technologies and AI West Africa.
All rights reserved. Proprietary and confidential.
CONFIDENTIAL · PATENT PENDING
-->

# STAR-POL-02: AI Systems Governance and Processing Controls

| Field | Value |
|---|---|
| Document ID | STAR-POL-02 |
| Version | 1.0 |
| Status | Draft |
| Classification | CONFIDENTIAL · PATENT PENDING |
| Date | May 2026 |
| Issuing Authority | Starisian Technologies |
| Cross-Reference | DVE-FRM-01, STAR-POL-01, STAR-POL-03, STAR-POL-04 |

---

## 1. Purpose and Scope

### 1.1 Purpose

1.1.1 This document establishes Starisian Technologies' AI systems governance and processing controls applicable to the SPARXSTAR platform and the DVE operational stack.

1.1.2 Starisian is the infrastructure authority for AI processing within DVE. This policy defines the engineering and operational constraints within which AIWA's AI processing governance decisions are implemented.

### 1.2 Authority

1.2.1 Starisian determines how approved AI processing operations are implemented safely and reliably. This policy does not grant Starisian authority to approve AI processing operations — that authority belongs to AIWA as defined in DVE-FRM-01, Section 6.

---

## 2. AI Processing Standards

### 2.1 Isolation Requirements

2.1.1 AI processing of governed artifacts must occur within Starisian's designated AI processing environments. These environments are isolated from general-purpose computing infrastructure.

2.1.2 Processing must not occur outside the DVE governance boundary. Starisian maintains the technical controls necessary to enforce this isolation requirement.

### 2.2 Governance Integration

2.2.1 All AI processing operations within DVE must be integrated with the Sieve governance enforcement mechanism. Starisian's AI processing infrastructure must support the Release Receipt validation requirement defined in DVE-FRM-01, Section 5.2.

2.2.2 AI processing systems operated by Starisian must not process a governed artifact without a valid Release Receipt for the requested processing operation.

### 2.3 Output Governance

2.3.1 Outputs generated from AI processing of governed artifacts must carry ArtifactGovernanceDeclaration provenance references in accordance with DVE-FRM-01, Section 8.2.1(c).

---

## 3. AI Model Governance

### 3.1 Model Custody

3.1.1 AI models trained on governed artifacts within the DVE are governed artifacts and remain within Starisian's custody within the DVE governance boundary.

3.1.2 Distribution or deployment of AI models trained on governed artifacts outside the DVE governance boundary requires AIWA authorisation. Starisian enforces this requirement through platform access controls.

---

*End of STAR-POL-02*

*Copyright (c) 2026 Starisian Technologies. All rights reserved. Proprietary and confidential. CONFIDENTIAL · PATENT PENDING*
