# System Analysis

**Date:** 05.05.2026  
**Law:** Lieferkettensorgfaltspflichtengesetz (LkSG)  
**LAW_EFFECTIVE_DATE:** 08.04.2026  
**Method:** Law-X-Ray  

---

## 1. Description

This file presents the structural model of system behavior under regulatory conditions,
derived from reproducibility, structural filtering, and validation.

The analysis focuses on:

* the core causal mechanism
* secondary mechanisms
* factor configuration

The model identifies structural conditions under which outcomes emerge,
including information control, self-reporting architecture, and verification limitations.

This analysis does not evaluate the law as a whole and does not make normative claims.
It reconstructs how the system operates at the mechanism level.

---

## 2. Core Mechanism

> internal interpretation → information control → limited verification → detection gap

Outcome: constrained detection capacity

Validation status: empirically confirmed

Basis:

* core mechanism reproduced across runs
* structurally stable after filtering
* no logical contradictions
* behavioral elements excluded from core

Core exclusions:

* incentive-driven behavior
* enforcement variability
  → treated as secondary or conditional

Incentives are excluded as they depend on actor behavior and are not structurally required.

Implication:

→ detection limitations are structurally embedded in information production
→ increasing enforcement alone does not eliminate the constraint

---

## 2.1 Mechanism Explanation

**internal interpretation → information control**
• cause: risk definitions and reporting criteria are internally determined by regulated entities
• factors: F1 — Discretion and Concentration of Powers, F7 — Conflict of Interest
• type: structural

**information control → limited verification**
• cause: control over generated data constrains independent access and auditability
• factors: F5 — Enforcement Gap, F7 — Conflict of Interest
• type: structural

**limited verification → detection gap**
• cause: restricted verification capacity reduces probability of detecting violations
• factors: F5 — Enforcement Gap
• type: structural

Secondary mechanisms explain variation, not the core outcome.

Only a limited number of independent secondary mechanisms are identified; other effects are treated as derived or reinforcing elements.

---

## 3. Secondary Mechanisms

### Mechanism 1

> regulatory pressure
→ internal interpretation (enabled by discretion)
→ strategic compliance behavior

Explanation

**regulatory pressure → internal interpretation**
• cause: legal obligations require companies to define and assess risks internally
• factors: F1 — Discretion and Concentration of Powers, F2 — Regulatory Pressure

**internal interpretation → strategic compliance**
• cause: flexibility in interpretation allows alignment with internal cost and risk preferences
• factors: F2 — Regulatory Pressure, F9 — Selective Application

Type: INDEPENDENT
Context: BEHAVIORAL

Validation status: empirically confirmed
Confidence level: medium

---

### Mechanism 2

> information control
→ transparency limitation
→ verification gap

Explanation

**information control → transparency limitation**
• cause: internally generated data is not fully observable or standardized
• factors: F7 — Conflict of Interest, F6 — Transparency Limitation

**transparency limitation → verification gap**
• cause: limited visibility constrains audit and enforcement capacity
• factors: F5 — Enforcement Gap, F11 — Sanctions Effectiveness

Type: DERIVED
Context: STRUCTURAL-OPERATIONAL

Validation status: empirically confirmed
Confidence level: high

---

## 4. Factors

| Factor | Name                                       | Value | Comment                         |
| ------ | ------------------------------------------ | ----- | ------------------------------- |
| F1     | Discretion and Concentration of Powers     | 5.9   | enables internal interpretation |
| F2     | Regulatory / Stimuli Pressure              | 6.3   | behavioral driver               |
| F3     | Secondary Effects                          | 4.6   | limited influence               |
| F4     | Control Concentration                      | 5.2   | supports structure              |
| F5     | Enforcement Gap (verification limitation)  | 5.7   | core constraint                 |
| F6     | Transparency Limitation                    | 4.7   | affects observability           |
| F7     | Conflict of Interest (information control) | 6.4   | central driver                  |
| F8     | System Complexity                          | 6.9   | amplifies mechanism             |
| F9     | Selective Application                      | 5.2   | variability layer               |
| F10    | Structural Stability                       | 6.3   | system persistence              |
| F11    | Sanctions Effectiveness                    | 5.0   | limits enforcement              |

Source: reproducibility aggregation

---

## 5. System Properties

### Core Mechanism

Level: SYSTEMIC
Scale: system-wide

Validation status: empirically confirmed


### Secondary Mechanisms

Level: PARTIAL
Scale: segmental

Validation status: empirically confirmed

---

## 6. Feedback Structure

> detection gap
→ reduced detection risk
→ information control
→ limited verification
→ detection gap

Explanation

**detection gap → reduced detection risk**
• cause: low detection probability reduces expected enforcement consequences
• factors: F5

**reduced risk → information control**
• cause: lower enforcement pressure allows continuation of internally controlled reporting
• factors: F5, F7

**information control → limited verification**
• cause: restricted data access constrains verification
• factors: F5

**limited verification → detection gap**
• cause: verification limits sustain low detection probability
• factors: F5

Validation status: partially confirmed

Loop Properties

Type: MIXED
Strength: medium
Stability: conditional

**Note:**
The feedback loop is not required for the core mechanism to operate
and should be interpreted as a reinforcing, non-essential dynamic.

---

## 7. Interpretation

The system operates through a structure where:

* risk definitions and reporting are internally generated
* information remains under control of regulated entities
* verification depends on controlled data access

→ outcomes are driven by information control and structural verification limits

---

## Final Point

The mechanism was derived through reproducible structural analysis
and validated against observed system behavior.

This indicates:

→ high structural consistency
→ strong internal coherence
→ alignment with observed compliance practices

---
