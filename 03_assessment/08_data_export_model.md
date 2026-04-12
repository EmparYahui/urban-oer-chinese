# 08 Data Export Model — Assessment Output Formats

## 🧠 Overview

This document defines how assessment data from the OER system can be exported for teaching, research, and documentation purposes.

It ensures that learner evidence and evaluation results can be used outside the system in a consistent format.

---

## 📊 Export purpose

Assessment data is exported for three main uses:

- **Teaching practice** → tracking learner progress
- **Research analysis** → qualitative and quantitative interpretation
- **Documentation** → reporting and institutional use

---

## 📁 1. Table export (CSV / spreadsheet)

This is the **main export format for teachers**.

### Structure:

| Field | Description |
|------|-------------|
| leu_id | Learner evidence unit ID |
| learner_id | Anonymised learner identifier |
| task_id | Associated learning task |
| mediation_score | 1–4 |
| multimodal_score | 1–4 |
| linguistic_score | 1–4 |
| oer_score | 1–4 |
| global_score | final aggregated score |

### Use cases:
- Excel tracking
- grading sheets
- classroom monitoring

---

## 📁 2. Textual export (qualitative report)

Used for **research and qualitative analysis**.

Includes:

- description of learner output
- mediation notes
- multimodal description
- teacher comments
- rubric interpretation

Format: structured text or document export (Word / PDF)

---

## 📁 3. Evidence export (structured record per task)

Each LEU can also be exported as a **single record**, including:

- context (task + setting)
- learner output description
- rubric scores
- short qualitative annotation

---

## 🧠 Export principles

- Data must remain anonymised
- No personal learner information is included
- Export formats must remain simple and readable
- Rubric scores must always follow the 1–4 scale
- Qualitative notes are optional but recommended

---

## 🔁 System role

This module connects assessment with external use:

> classroom practice → evaluation → documentation → research use

---

## 🔁 Navigation

← Back to the OER system overview → [README](../README.md)
