# 06 Assessment Dataset Schema — Learning Corpus Structure

## 🧠 Overview

This document defines the **data structure of learner-generated evidence** within the Urban Linguistic Landscape OER system.

It operationalises assessment outputs as a **structured research corpus**, enabling systematic analysis of mediation, multimodality, and OER quality.

---

## 🧩 Unit of analysis: Learning Evidence Unit (LEU)

Each learner production is treated as a **Learning Evidence Unit (LEU)**.

An LEU is the smallest analysable unit in the system.

---

## 📊 LEU data schema

### 1. Identifiers

| Field | Description |
|------|-------------|
| `leu_id` | Unique identifier of the evidence unit |
| `learner_id` | Anonymised learner code |
| `task_id` | Reference to Learning Task (02 module) |
| `session_id` | Teaching/learning session identifier |
| `date` | Timestamp of production |

---

### 2. Contextual metadata

| Field | Description |
|------|-------------|
| `urban_input_type` | Sign / image / sound / interaction / mixed |
| `location_context` | Urban environment category |
| `language_context` | Languages present in input |
| `learning_stage` | Observation / mediation / production / reflection |

---

### 3. Mediation layer

| Field | Description |
|------|-------------|
| `mediation_operations` | rewrite / translate / adapt / select / transform |
| `intercultural_shift` | low / medium / high |
| `audience_orientation` | self / peers / external audience |

---

### 4. Multimodal layer

| Field | Description |
|------|-------------|
| `modes_used` | text / image / audio / video |
| `mode_interaction` | additive / integrated / hybrid |
| `semiotic_density` | low / medium / high |

---

### 5. Linguistic layer (A1–A2)

| Field | Description |
|------|-------------|
| `accuracy_level` | 1–4 (rubric-aligned) |
| `lexical_range` | basic / emerging / functional |
| `pragmatic_clarity` | low / medium / high |

---

### 6. Assessment layer

| Field | Description |
|------|-------------|
| `mediation_score` | 1–4 |
| `multimodal_score` | 1–4 |
| `linguistic_score` | 1–4 |
| `oer_potential_score` | 1–4 |
| `global_score` | aggregated index |

---

### 7. OER dimension

| Field | Description |
|------|-------------|
| `reusability` | low / medium / high |
| `adaptability` | low / medium / high |
| `clarity_external_use` | low / medium / high |

---

### 8. AR integration (if applicable)

| Field | Description |
|------|-------------|
| `ar_present` | yes / no |
| `spatial_anchor_quality` | low / medium / high |
| `context_coherence` | low / medium / high |

---

## 🧠 System role

This schema transforms learner outputs into a **structured multimodal corpus for educational research and assessment analytics**.

---

## 🔁 Navigation

← Back to the OER system overview → [README](../README.md)
