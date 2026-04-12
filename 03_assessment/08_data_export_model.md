# 08 Data Export Model — Assessment Output Formats

## 🧠 Overview

This document defines the **export layer of the Assessment system**, enabling the use of learner evidence beyond the OER environment.

It connects structured corpus data (LEUs) with external contexts of use:

- teaching practice
- research analysis
- institutional documentation

---

## 🧩 Export architecture

Assessment data is exported through **three complementary layers**:

---

## 📁 1. Structured dataset export (quantitative layer)

This format supports **systematic comparison and aggregation**.

### Core fields

| Field | Description |
|------|-------------|
| leu_id | Learning Evidence Unit identifier |
| learner_id | Anonymised learner code |
| task_id | Associated learning task |
| mediation_score | 1–4 rubric score |
| multimodal_score | 1–4 rubric score |
| linguistic_score | 1–4 rubric score |
| oer_score | 1–4 rubric score |
| global_score | aggregated performance indicator |

### Function

- cross-task comparison
- progress tracking
- statistical analysis
- dashboard integration

---

## 📁 2. Qualitative export (interpretive layer)

This format preserves **meaningful pedagogical and research interpretation**.

### Content includes:

- description of learner production
- mediation process notes
- multimodal composition analysis
- teacher or researcher annotations
- contextual interpretation of performance

### Function

- discourse analysis
- mediation studies
- qualitative research coding
- pedagogical reflection

---

## 📁 3. Learning Evidence Unit export (full record layer)

This format exports a **complete LEU as a self-contained analytical object**.

It includes:

- contextual information (task + environment)
- input description (urban stimulus)
- mediation process summary
- output description (learner artefact)
- evaluation summary (rubric + notes)

### Function

- case study analysis
- longitudinal tracking
- multimodal interpretation
- corpus triangulation

---

## 🧠 Export principles

All exports must respect the following principles:

- learner anonymity must be preserved
- no personally identifying data is included
- outputs must remain interoperable across tools
- rubric scores are always preserved on a 1–4 scale
- qualitative data complements, not replaces, structured data
- exports must preserve traceability to the original LEU

---

## 🔄 System integration

The export layer connects the full system chain:

> Learning activity → LEU → Annotation → Dataset → Export → Research / Teaching use

It functions as the **external interface of the Assessment system**.

---

## 🧠 Design principle

The export system is not a reporting tool.

It is a **transformation layer that converts educational interaction into research-ready and pedagogically reusable data**.

---

## 🔁 Navigation

← Back to Assessment system → [README](../README.md)
