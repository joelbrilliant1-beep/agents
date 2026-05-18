---
name: Corporate Policy
description: Generic usage, data handling, compliance, and evidence-led communication policy template
---

# Corporate Usage & Data Handling Policy Template

**Document Owner:** Project Owner
**Version:** 1.0
**Effective Date:** Replace with project date
**Classification:** Replace with project classification

---

## 1. Purpose

This policy defines how a reporting, analytics, or AI-assisted insight tool should handle usage, data, generated narratives, exports, and evidence-backed communication.

The tool should help users create reliable reports from approved source documents while preserving data security, de-identification, human review, and clear separation between verified facts and projected outcomes.

---

## 2. Scope

This policy applies to:
- All employees, contractors, or agents who use the project
- All data processed by the project, including uploaded reports, generated narratives, exports, and audit metadata
- All environments used by the project, including local, staging, and production

---

## 3. Core Principles

- **De-identification is mandatory** — No customer name, logo, or PII may ever be stored or displayed.
- **Single Source of Truth** — Only approved source documents and datasets may be used.
- **Additive Uploads** — Multiple approved report types can be combined in one session without losing data.
- **Evidence-led Communication** — Reports should separate **Verdict** (always visible), **Evidence** (supporting detail), and **Appendix** (methodology and caveats).
- **Transparency** — Every metric must be traceable to its source document via provenance badges.
- **Ethical AI** — The AI narrative must never hallucinate numbers or overstate impact. Computed fields (hours, dollars) are locked unless explicitly labelled "Customer Verified".

---

## 4. Data Handling Rules

### 4.1 Acceptable Inputs
- Approved aggregate analytics exports
- Approved outcome reports, ROI studies, partnership overviews, or research documents
- Public or licensed benchmark data where the licence permits the intended use

### 4.2 Prohibited Actions
- Uploading screenshots, manual metrics, or any file containing PII
- Bypassing the mandatory de-identification confirmation gate
- Manually overriding computed fields without clear "Customer Verified" labelling
- Sharing raw uploaded PDFs externally

### 4.3 De-identification & Date Range
- Users must confirm via the mandatory checkbox that files are fully de-identified.
- Users must enter the exact date range covered by the uploaded reports before processing.

---

## 5. AI Narrative Generation & Evidence Structure

- The AI generates narratives **only** from verified, de-identified data extracted from uploaded PDFs.
- The dashboard **must** follow an evidence-led model:
  - **Layer 1 - Verdict**: headline, key metrics, AI narrative, and data period
  - **Layer 2 - Evidence**: benchmarks, platform health, engagement patterns, outcome quality, representation, and efficiency analysis where relevant
  - **Layer 3 - Appendix**: methodology, assumptions, talk tracks, advisor notes, and verified overrides
- All numbers in the final report must match source PDFs or be clearly labelled "Estimated".
- "Actuals vary" language must appear on any forward-looking projection.

---

## 6. Export & Sharing Rules

- Reports may only be shared externally after final human review by the responsible account or project owner.
- Exported PPTX/PDF must include the data-period banner, source provenance badges, and evidence-led structure.
- Internal sharing of raw reports is permitted only with authorised project stakeholders.

---

## 7. Security & Compliance

- The tool should align with the organisation's AI, privacy, and data-handling obligations.
- All processing occurs with de-identified data only.
- No data is used to train external models.
- Audit logs of uploads and generations are maintained.

---

## 8. Roles & Responsibilities

| Role                  | Responsibility |
|-----------------------|----------------|
| **Account Owner**     | Ensure files are de-identified, review final report before client delivery, follow the evidence-led structure |
| **Product Team**      | Maintain accurate extraction, enforce policy in code, keep the evidence-led structure intact |
| **Security Team**     | Periodic audits of uploaded files and logs |
| **Leadership**        | Approve any exceptions to this policy |

---

## 9. Violations

Any breach (uploading PII, bypassing de-ID gate, manual fabrication of metrics, or breaking the evidence-led structure) will be treated as a serious compliance incident and may result in disciplinary action.

---

## 10. Acknowledgement

All users must acknowledge this policy before first use of the project.

---

**Approved by:**
Project Owner and Security/Compliance Owner
Replace with approval date

---

**End of Document**
