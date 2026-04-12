# 06 Assessment Dataset Schema — Learning Corpus Structure

## 🧠 Overview

This document defines the **structured dataset schema** for learner-generated evidence in the Urban Linguistic Landscape OER system.

It operationalises assessment outputs as a **research-ready multimodal corpus**, enabling systematic analysis of mediation, multimodality, and OER production.

The schema is fully aligned with the **Learning Evidence Unit (LEU)** model.

---

## 🧩 Unit of analysis: Learning Evidence Unit (LEU)

Each learner production is represented as a **Learning Evidence Unit (LEU)**.

The LEU is the smallest analysable unit in the corpus and functions as the central entry of the dataset.

---

## 📊 Dataset structure overview

The corpus is organised into **eight analytical dimensions**.

Each LEU is encoded through these dimensions for research and assessment purposes.

---

## 1. Identifiers

| Field | Description |
|------|-------------|
| leu_id | Unique identifier of the evidence unit |
| learner_id | Anonymised learner code |
| task_id | Reference to Learning Task (Module 02) |
| session_id | Teaching/learning session identifier |
| timestamp | Time of production |

---

## 2. Contextual dimension

| Field | Description |
|------|-------------|
| urban_input_type | sign / image / audio / interaction / multimodal environment |
| spatial_context | urban setting category (street / transport / institution / hybrid) |
| language_environment | languages present in input |
| learning_phase | observation / mediation / production / reflection |

---

## 3. Mediation dimension

| Field | Description |
|------|-------------|
| mediation_operations | interpret / translate / adapt / select / transform |
| mediation_complexity | low / medium / high |
| intercultural_shift | minimal / moderate / strong |
| audience_orientation | self / peer / external |

---

## 4. Multimodal dimension

| Field | Description |
|------|-------------|
| modes_used | text / image / audio / video / mixed |
| multimodal_configuration | additive / integrated / hybrid |
| semiotic_density | low / medium / high |

---

## 5. Linguistic dimension (A1–A2)

| Field | Description |
|------|-------------|
| grammatical_control | 1–4 scale (rubric-aligned) |
| lexical_range | basic / emerging / functional |
| pragmatic_clarity | low / medium / high |

---

## 6. Assessment dimension

| Field | Description |
|------|-------------|
| mediation_score | 1–4 |
| multimodal_score | 1–4 |
| linguistic_score | 1–4 |
| oer_potential_score | 1–4 |
| global_assessment_index | derived composite indicator |

---

## 7. OER dimension

| Field | Description |
|------|-------------|
| reusability | low / medium / high |
| adaptability | low / medium / high |
| external_clarity | low / medium / high |

---

## 8. AR dimension (if applicable)

| Field | Description |
|------|-------------|
| ar_used | yes / no |
| spatial_alignment_quality | low / medium / high |
| contextual_coherence | low / medium / high |

---

## 🧠 System role

This dataset schema transforms learner outputs into a **structured multimodal corpus for educational research, assessment analytics, and OER evaluation**.

It ensures:

- comparability across tasks
- consistency of annotation
- traceability of mediation processes
- research reproducibility

---

## 🔁 Navigation

← Back to the OER system overview → [README](../README.md)
