<!--
CONFIDENTIAL · PATENT PENDING
Proprietary and confidential. All rights reserved.
-->

# AIWA-DOC-01: Document Classification and Governance Artifact Taxonomy

| Field | Value |
|---|---|
| Document ID | AIWA-DOC-01 |
| Version | 1.0 |
| Status | Draft |
| Classification | CONFIDENTIAL · PATENT PENDING |
| Date | May 2026 |
| Issuing Authority | AI West Africa |
| Cross-Reference | DVE-FRM-01, AIWA-DOC-02, AIWA-DOC-03 |

---

## 1. Purpose and Scope

### 1.1 Purpose

1.1.1 This document establishes the classification framework and governance artifact taxonomy applicable to all documents issued under AIWA authority and all artifacts that enter the DVE governance pipeline.

1.1.2 Document classification determines the sensitivity, handling requirements, and distribution restrictions applicable to a document. Governance artifact taxonomy defines the categories of artifacts processed within the DVE and the governance rules applicable to each category.

### 1.2 Scope

1.2.1 This document applies to:

(a) All AIWA governance documents;
(b) All Starisian governance documents that reference AIWA governance authority;
(c) All DVE-series operational documents;
(d) All artifacts processed within the DVE governance pipeline.

---

## 2. Document Classification Levels

### 2.1 Classification Hierarchy

2.1.1 AIWA documents are classified at one of the following levels:

| Classification | Definition |
|---|---|
| PUBLIC | Documents approved for unrestricted distribution by AIWA |
| RESTRICTED | Documents for authorised AIWA stakeholders only |
| CONFIDENTIAL | Documents for AIWA and Starisian leadership and designated personnel |
| CONFIDENTIAL · PATENT PENDING | Confidential documents that contain or reference patent-sensitive material |

2.1.2 All documents in this repository carry a minimum classification of CONFIDENTIAL unless AIWA has expressly designated a document as PUBLIC.

### 2.2 Classification Authority

2.2.1 AIWA is the classification authority for all AIWA-series and DVE-series documents. Starisian is the classification authority for STAR-POL series documents.

---

## 3. Governance Artifact Taxonomy

### 3.1 Artifact Categories

3.1.1 The following artifact categories are recognised within the DVE governance pipeline:

| Category | Definition |
|---|---|
| Work | An intellectual creation fixed in tangible form, submitted to AIWA by an individual contributor |
| Folklore | Expression of community cultural heritage with no identifiable individual author, transmitted through generations |
| TCE | Traditional Cultural Expression — protected under Gambian law |
| Derived Work | An artifact created by processing one or more governed artifacts |
| AI Model | A computational model trained, fine-tuned, or derived from governed artifacts |
| Dataset | A structured collection of governed artifacts assembled for AI processing |
| Governed Artifact | Any artifact that has entered the DVE governed pipeline, regardless of category |

### 3.2 Chain of Title

3.2.1 "Chain of Title" means the documented ownership history and authorisation record establishing a contributor's legal authority to grant rights in a Work. The Chain of Title for a Work includes all assignments, licences, contributor consents, publishing rights, master rights, synchronisation rights, sample clearances, AI model output rights, and third-party permissions applicable to the Work.

3.2.2 AIWA requires a complete and verified Chain of Title for every Work entering the DVE governance pipeline. Chain of Title verification is a mandatory step in the contributor intake procedure defined in AIWA-DOC-03.

3.2.3 An incomplete or unverifiable Chain of Title prevents intake. Works with unresolved Chain of Title defects are held pending resolution and do not enter the active DVE pipeline.

### 3.3 Rights Category Separation

3.3.1 The rights applicable to a governed Work are categorised separately. Each category of rights is governed independently within the DVE. Consent and permissions must be recorded per category at intake.

| Rights Category | Definition | Governed Separately |
|---|---|---|
| Distribution | Rights to distribute the Work in physical or digital form | Yes |
| Streaming | Rights to make the Work available for continuous transmission | Yes |
| Synchronisation | Rights to synchronise the Work with visual media | Yes |
| Archival | Rights to store and preserve the Work for non-commercial purposes | Yes |
| Translation and Adaptation | Rights to translate or adapt the Work into another form | Yes |
| Corpus Development | Rights to include the Work in a structured collection for research purposes | Yes |
| Computational Rights | Rights to use the Work in AI training, inference, model development, or other computational processing operations | Yes |
| Public Display | Rights to display the Work in public contexts | Yes |

3.3.2 "Computational Rights" are separate and distinct from distribution, streaming, synchronisation, archival, translation, corpus development, and public display rights. A contributor's consent to one rights category does not imply consent to any other rights category.

3.3.3 A Release Receipt from the Sieve authorises only the specific rights category and processing operation requested. It does not authorise processing under any other rights category.

### 3.4 Artifact Governance Requirements by Category

3.4.1 Each artifact category carries the following default governance requirements:

| Category | Default Dataset Tier | Consent Required | Cultural Restriction Default |
|---|---|---|---|
| Work | Tier 2 | Yes — individual contributor | No |
| Folklore | Tier 3 | Yes — community authority | Yes |
| TCE | Tier 3 | Yes — AIWA and community authority | Yes |
| Derived Work | Inherited from source | Inherited from source | Inherited from source |
| AI Model | Tier 2 | Inherited from training dataset | Inherited from training dataset |
| Dataset | Derived from composition | Derived from composition | Derived from composition |

### 3.5 Derivative Governance

3.5.1 A Derived Work inherits Governance Metadata from each source governed artifact that contributed to its creation. This is the Policy Inheritance principle: the most restrictive applicable governance constraint from any contributing source artifact governs the Derived Work, unless AIWA has expressly authorised a less restrictive governance profile.

3.5.2 Derived Works are subject to the following additional governance requirements:

(a) The Provenance Object for a Derived Work must reference all source governed artifacts and the processing operations that produced the derivation;
(b) The ArtifactGovernanceDeclaration for a Derived Work must record the Release Receipts that authorised each processing step in its derivation;
(c) Cultural restriction designations attached to any source artifact propagate automatically to the Derived Work;
(d) Computational Rights restrictions attached to any source artifact propagate automatically to AI Model and Dataset artifacts derived from it.

3.5.3 **Revocation propagation**: Revocation of a permission for a source governed artifact triggers a governance review of all Derived Works that relied upon that permission. AIWA determines the applicable remedy for affected Derived Works. Pending AIWA's determination, affected Derived Works are placed in QUARANTINE.

3.5.4 **AI Model derivation governance**: An AI Model trained on, fine-tuned from, or derived from one or more governed artifacts inherits the most restrictive Governance State and dataset tier applicable to any artifact in its training dataset. The AI Model's ArtifactGovernanceDeclaration must record the full training dataset composition and the Release Receipts authorising each dataset use.

---

*End of AIWA-DOC-01*

*AI West Africa is a Busumbala Born, Gambian Grown Company.*

*Copyright (c) 2026 AI West Africa. All rights reserved.*
