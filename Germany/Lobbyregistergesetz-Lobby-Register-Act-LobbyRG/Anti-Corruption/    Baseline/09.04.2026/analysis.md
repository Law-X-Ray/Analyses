# System Analysis

Analysis Date: 28.04.2026

Law: Lobbyregistergesetz (Deutschland), reformierte Fassung 2024 (version as of 09.04.2026)

Method: Law-X-Ray

---

## 1. Description

This file presents the **structural model of corruption risk formation within the system**,
derived from reproducibility, coverage analysis, and validation.

The analysis focuses on:

* the core causal mechanism
* secondary mechanisms
* factor configuration

The model identifies **structural conditions under which specific outcomes emerge**,
including information asymmetry, verification limitations, and incentive effects.

This analysis does **not evaluate the law as a whole** and does not make normative claims.
It reconstructs how the system operates at the mechanism level.

---

![Core mechanism](/assets/diagrams/lksg/lksg-mechanisms_08-04-2026_.png)

## 2. Core Mechanism

> Self-declaration
> → information control
> → selective disclosure
> → limited verification
> → detection gap

Outcome: sustained incentive to underreport

**Validation status: empirically confirmed**
→ mechanism consistently reproduced across runs
→ core structure directly observed in system design
→ partial empirical confirmation of downstream effects

**Basis:**

* core mechanism present in all runs
* high saturation (no new mechanisms in final run)
* no structural contradictions

---

## 2.1 Mechanism Explanation

**self-declaration → information control**
• cause: regulated entities generate and submit their own data, retaining control over content and completeness
• factors: F7

**information control → selective disclosure**
• cause: control over reporting allows selective inclusion and omission of information
• factors: F7

**selective disclosure → limited verification**
• cause: verification depends on disclosed data, limiting independent assessment
• factors: F5, F7

**limited verification → detection gap**
• cause: incomplete verification reduces the probability of detecting inconsistencies
• factors: F5

**detection gap → incentive to underreport**
• cause: low probability of detection reduces expected costs of non-compliance
• factors: F2

---

## 3. Secondary Mechanisms

### Mechanism 1

> selective enforcement
> → uneven control coverage
> → reinforcement of underreporting behavior

Explanation
selective enforcement → uneven control coverage
• cause: limited detection capacity leads to concentration of enforcement on visible or high-risk cases
• factors: F9, F5

uneven control coverage → reinforcement of underreporting behavior
• cause: actors adjust behavior based on perceived enforcement patterns, maintaining selective disclosure
• factors: F2

Type: DERIVED (from core mechanism)
Dependency strength: STRONG

---

### Validation Status

Empirically partially confirmed
→ consistent with system structure
→ observed indirectly through enforcement patterns
→ dependent on activation of core mechanism

**Basis:**

• no independent entry identified
• appears only downstream of core mechanism
• not reproduced as independent chain across runs

---

## 4. Factors

| Factor | Name                          | Value | Stability | Comment                            |
| ------ | ----------------------------- | ----- | --------- | ---------------------------------- |
| F1     | Discretion / Interpretability | 4.4   | 🟢        | secondary role                     |
| F2     | Incentive Structure           | 5.6   | 🟢        | drives underreporting incentives   |
| F3     | Secondary Effects             | 5.2   | 🟢        | moderate influence                 |
| F4     | Control Concentration         | 4.7   | 🟢        | limited structural role            |
| F5     | Verification Gap              | 5.1   | 🟢        | defines detection limitation       |
| F6     | Transparency Limitation       | 4.2   | 🟢        | formal transparency, limited depth |
| F7     | Information Control           | 6.2   | 🟢        | central driver                     |
| F8     | System Complexity             | 4.8   | 🟢        | moderate amplification             |
| F9     | Application Variability       | 4.6   | 🟡        | partial variability                |
| F10    | Structural Stability          | 5.7   | 🟢        | stable configuration               |
| F11    | Sanctions Effectiveness       | 4.4   | 🟢        | limited deterrence                 |

Source: reproducibility aggregation

---

## 5. System Properties

### Core Mechanism

**Level: SYSTEMIC**
**Scale: system-wide**

**Validation status: empirically confirmed**
→ system-level behavior directly follows from structural design
→ no adjustment required

---

### Secondary Mechanisms

**Level: DERIVED**
**Scale: segmental**

**Validation status: partially confirmed**
→ dependent on core mechanism
→ no independent activation

---

## 6. Feedback Structure

> detection gap
> → reinforces incentive to underreport
> → increases selective disclosure
> → reinforces information control

**Explanation**
detection gap → reinforces incentive to underreport
• cause: low detection probability reduces expected costs
• factors: F2

incentive to underreport → selective disclosure
• cause: actors adapt reporting behavior to minimize exposure
• factors: F2, F7

selective disclosure → information control
• cause: selective reporting increases control over available information
• factors: F7

information control → detection gap
• cause: controlled information limits verification capacity
• factors: F5, F7

**Validation status: partially confirmed**
→ loop structurally consistent across runs
→ partially supported by observed behavior

### Loop Properties

**Type:** reinforcing

**Strength:** high
• driven by F2, F5, F7
• consistent structural reinforcement
• no breaks identified

**Stability:** high
• persists under variation
• reproduced across runs
• no counteracting mechanisms identified

**Implication:**
→ the feedback loop stabilizes underreporting behavior
→ system tends toward persistent information asymmetry

---

## 7. Interpretation

The system operates through a structure where:

* information is generated and controlled by regulated actors
* verification depends on disclosed data
* detection probability is structurally limited

Within this configuration:

→ outcomes are driven by information control and verification constraints

rather than by enforcement capacity alone

---

### Interpretation Note

Empirical validation confirms that:

* the mechanism derived from structural analysis
* corresponds to observed system behavior

Residual uncertainty reflects:

* downstream effects (verification, enforcement)
* not errors in core mechanism

---

## Final Point

The mechanism was derived through reproducible structural analysis
and confirmed through real-world system structure.

This indicates:

→ **low probability of structural error**
→ **low probability of missing major mechanisms**
→ **high alignment between model and system design**

---
