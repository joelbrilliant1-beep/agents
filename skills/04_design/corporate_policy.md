---
name: Corporate Policy
description: Impact Studio corporate usage, data handling, and Pyramid Communication policy
---

# Impact Studio – Corporate Usage & Data Handling Policy

**Document Owner:** Sapia.ai Product & Security Team  
**Version:** 1.0  
**Effective Date:** 19 February 2026  
**Classification:** Internal – Confidential

---

## 1. Purpose

Impact Studio is Sapia.ai's internal executive reporting tool. It enables Customer Success Managers to rapidly generate board-ready Impact Reports using only Quick Suite PDF exports and approved partner reports (churn/ROI analysis).

The tool exists **solely** to demonstrate measurable client value, support renewals, expansions, and QBRs — while upholding the highest standards of data security, de-identification, ethical AI, and Pyramid Communication.

---

## 2. Scope

This policy applies to:
- All Sapia.ai employees and contractors who use Impact Studio
- All data processed by the tool (Quick Suite PDFs, post-hire reports, generated narratives, exports)
- All environments (local, staging, production)

---

## 3. Core Principles

- **De-identification is mandatory** — No customer name, logo, or PII may ever be stored or displayed.
- **Single Source of Truth** — Only Quick Suite PDF exports and approved partner reports may be uploaded.
- **Additive Uploads** — Quick Suite and Post-Hire reports can be combined in one session without losing data.
- **Pyramid Communication** — All reports follow the 3-layer structure: **Verdict** (always visible) → **Evidence** (collapsible) → **Appendix** (collapsed at bottom).
- **Transparency** — Every metric must be traceable to its source document via provenance badges.
- **Ethical AI** — The AI narrative must never hallucinate numbers or overstate impact. Computed fields (hours, dollars) are locked unless explicitly labelled "Customer Verified".

---

## 4. Data Handling Rules

### 4.1 Acceptable Inputs
- Quick Suite PDF exports (Overview, Hired Stats, Device Type, Sentiment & Feedback, Submission Time, Adhoc Time, Chat Interview, etc.)
- Approved partner reports (churn analysis, ROI studies, partnership overviews)

### 4.2 Prohibited Actions
- Uploading screenshots, manual metrics, or any file containing PII
- Bypassing the mandatory de-identification confirmation gate
- Manually overriding computed fields without clear "Customer Verified" labelling
- Sharing raw uploaded PDFs externally

### 4.3 De-identification & Date Range
- Users must confirm via the mandatory checkbox that files are fully de-identified.
- Users must enter the exact date range covered by the uploaded reports before processing.

---

## 5. AI Narrative Generation & Pyramid Structure

- The AI generates narratives **only** from verified, de-identified data extracted from uploaded PDFs.
- The dashboard **must** follow the Pyramid model:
  - **Layer 1 – Verdict** (always visible): Headline + 3 hero metrics + AI narrative + Data Period badge
  - **Layer 2 – Evidence** (collapsible): Benchmarking, Platform Health, Device Insights, Engagement Patterns, Hired Pool Quality, DEI Impact, Efficiency Journey
  - **Layer 3 – Appendix** (collapsed): Methodology, CSM Talk Tracks, AI Advisor, Renewal Radar, Verified Overrides
- All numbers in the final report must match source PDFs or be clearly labelled "Estimated".
- "Actuals vary" language must appear on any forward-looking projection.

---

## 6. Export & Sharing Rules

- Reports may only be shared with clients after final human review by the responsible CSM.
- Exported PPTX/PDF must include the Data Period banner, source provenance badges, and Pyramid structure.
- Internal sharing of raw reports is permitted only within Sapia.ai.

---

## 7. Security & Compliance

- The tool aligns with Sapia.ai's ISO 42001 AI Management System.
- All processing occurs with de-identified data only.
- No data is used to train external models.
- Audit logs of uploads and generations are maintained.

---

## 8. Roles & Responsibilities

| Role                  | Responsibility |
|-----------------------|----------------|
| **CSM**               | Ensure files are de-identified, review final report before client delivery, follow Pyramid structure |
| **Product Team**      | Maintain accurate extraction, enforce policy in code, keep Pyramid structure intact |
| **Security Team**     | Periodic audits of uploaded files and logs |
| **Leadership**        | Approve any exceptions to this policy |

---

## 9. Violations

Any breach (uploading PII, bypassing de-ID gate, manual fabrication of metrics, breaking Pyramid structure) will be treated as a serious compliance incident and may result in disciplinary action.

---

## 10. Acknowledgement

All users must acknowledge this policy before first use of Impact Studio.

---

**Approved by:**  
Sapia.ai Head of Product & Head of Security  
19 February 2026

---

**End of Document**
