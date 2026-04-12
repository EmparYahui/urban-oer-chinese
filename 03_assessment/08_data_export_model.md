# 08 Data Export Model — Corpus Interoperability Layer

## 🧠 Overview

This document defines how the assessment corpus can be exported for:
- research analysis
- statistical processing
- qualitative coding tools
- OER dissemination

---

## 🧩 Export formats

The system supports three export layers:

### 1. Structured table export (CSV)

Recommended for:
- Excel
- Google Sheets
- basic analytics

**Core columns:**
- leu_id
- learner_id
- task_id
- mediation_score
- multimodal_score
- linguistic_score
- oer_score
- global_score

---

### 2. Qualitative export (JSON)

Recommended for:
- corpus linguistics tools
- multimodal analysis
- computational research

Structure:

```json
{
  "leu_id": "",
  "context": {},
  "mediation": {},
  "multimodal": {},
  "linguistic": {},
  "assessment": {},
  "oer": {},
  "ar": {}
}

---

## 🔁 Navigation

← Back to the OER system overview → [README](../README.md)
