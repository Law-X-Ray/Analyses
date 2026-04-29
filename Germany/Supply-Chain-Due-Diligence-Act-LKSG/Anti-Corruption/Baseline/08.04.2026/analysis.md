# System Analysis

Analysis Date: 16.04.2026

Law: Lieferkettensorgfaltspflichtengesetz (LkSG), version as of 08.04.2026

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

Entry condition: discretion      
> → self-reporting  
> → information control  
> → verification gap  
> → low detection  
> → incentive distortion  
 
Outcome: reduced enforcement effectiveness  
Explanation:
incentive distortion → reduced enforcement effectiveness  
• cause: persistent incentives for formal compliance reduce the effectiveness of enforcement mechanisms, as compliance appears satisfied without substantive changes  
• factors: F2, F11

**Validation status: empirically confirmed**  
→ mechanism consistently reproduced across runs 
→ theoretical structure matches real-world cases
→ no probability adjustment required

**Basis:**

* core mechanism present in all runs 
* high saturation (no new mechanisms in final runs)
* no structural contradictions

---

## 2.1 Mechanism Explanation

**discretion → self-reporting**  
• cause: regulatory discretion allows companies to define how compliance is reported, enabling self-reporting mechanisms 
• factors: F1  

**self-reporting → information control**  
• cause: companies generate and disclose compliance data themselves, gaining control over information  
• factors: F1, F7  

**information control → verification gap**  
• cause: verification depends on information controlled by the regulated actor, limiting independent assessment  
• factors: F5, F7  

**verification gap → low detection**  
• cause: the verification gap reduces the probability of identifying violations  
• factors: F5  

**low detection → incentive distortion**  
• cause: reduced likelihood of detection shifts incentives toward formal compliance instead of substantive compliance  
• factors: F2  

---

## 3. Secondary Mechanisms  

### Mechanism 1  

> regulatory pressure  
> → internal interpretation of requirements 
> → strategic compliance behavior  

Explanation  
regulatory pressure → internal interpretation of requirements  
• cause: regulatory requirements are broad and allow interpretation, leading organizations to internally define how compliance is understood  
• factors: F1, F9  
internal interpretation → strategic compliance behavior  
• cause: flexible interpretation enables companies to adapt behavior in a way that satisfies formal requirements while optimizing internal objectives  
• factors: F2, F9    

Type: INDEPENDENT (separate entry)   
Dependency strength: N/A  

### Mechanism 2  

> information distortion  
> → enforcement gap  
> → reduced sanction effectiveness  

Explanation    
information distortion → enforcement gap  
• cause: distorted or selectively presented information limits the ability of authorities to assess actual compliance conditions  
• factors: F5, F7  
enforcement gap → reduced sanction effectiveness  
• cause: limited detection and constrained enforcement capacity reduce the likelihood and impact of sanctions  
• factors: F5, F11  

Type: DERIVED (from core mechanism)  
Origin:
emerges from information control within the core mechanism, 
where controlled or selective information enables distortion and limits enforcement accuracy  
  
Dependency strength: STRONG  
• collapse_without_core: YES  
• alternative_entry: NO   
• core_link_overlap: YES  

---

### Validation Status  

Empirically confirmed  
→ observed in real-world cases  
→ consistent with the core mechanism  
→ variability reflects context-dependent activation  

**Basis:**  

• occurs in some runs but is not universal  
• not part of the invariant core  
• supported by empirical observations  

---

## 4. Factors

| Factor | Name                          | Value | Stability | Comment                             |
| ------ | ----------------------------- | ----- | --------- | ----------------------------------- |
| F1     | Discretion / Interpretability | 5.9   | 🟢        | contributes to entry via discretion |
| F2     | Incentive Structure           | 6.2   | 🟢        | drives incentive structure          |
| F3     | Secondary Effects             | 4.5   | 🟢        | secondary influence                 |
| F4     | Control Concentration         | 5.3   | 🟢        | supports control structure          |
| F5     | Verification Gap              | 5.5   | 🟢        | defines verification limitation     |
| F6     | Transparency Limitation       | 4.9   | 🟢        | reflects transparency constraint    |
| F7     | Information Control           | 6.4   | 🟢        | central driver: information control |
| F8     | System Complexity             | 6.9   | 🟢        | amplifies system behavior           |
| F9     | Application Variability       | 5.3   | 🟢        | allows variability                  |
| F10    | Structural Stability          | 6.3   | 🟢        | stable structural component         |
| F11    | Sanctions Effectiveness       | 4.8   | 🟢        | limits enforcement impact           |

Source: reproducibility aggregation 

---

## 5. System Properties

### Core Mechanism

**Level: SYSTEMIC**  
**Scale: system-wide**

**Validation status: empirically confirmed**  
→ system-level behavior observed in practice  
→ no adjustment required

---

### Secondary Mechanisms

**Level: PARTIAL**  
**Scale: segmental**  

**Validation status: empirically confirmed**  
→ system-consistent but condition-dependent

---

## 6. Feedback Structure

> low detection  
> → reinforces incentive distortion  
> → increases selective disclosure  
> → reinforces information control   

**Explanation**  
low detection → reinforces incentive distortion  
• cause: low probability of detection reduces expected costs of non-compliance, strengthening incentives for formal rather than substantive compliance  
• factors: F2  

incentive distortion → selective disclosure  
• cause: when incentives favor formal compliance, organizations selectively disclose information that satisfies requirements while omitting unfavorable data  
• factors: F2, F7  

selective disclosure → information control  
• cause: selective reporting increases control over the information available to regulators and external observers  
• factors: F7  

information control → low detection  
• cause: controlled and incomplete information further limits verification capacity, reducing detection probability  
• factors: F5, F7  

**Validation status: empirically confirmed**  
→ loop observed across runs 
→ consistent with real-world behavior

### Loop Properties  

**Type:** reinforcing  

**Strength:** high  
• the loop is driven by multiple reinforcing links (information control ↔ verification gap ↔ low detection)  
• core factors (F2, F5, F7) consistently support each transition  
• no structural breaks identified  


**Stability:** high  
• the loop does not depend on a single element and persists under variation in individual links  
• observed consistently across runs and validation cases  
• no counteracting mechanisms identified within the system  


**Implication:**   
→ the feedback loop amplifies and stabilizes the core mechanism  
→ once activated, the system tends to maintain low detection and incentive distortion over time  

---

## 7. Interpretation

The system operates through a structure where:

* information is generated and controlled by regulated actors
* verification depends on disclosed data
* detection probability depends on verification limitations

Within this configuration:

→ outcomes are structurally driven by information control and verification constraints

rather than by direct enforcement alone

---

### Interpretation Note

Empirical validation confirms that:

* the mechanism derived from structural analysis
* corresponds to real-world system behavior

Residual uncertainty reflects:

* context-dependent activation (secondary mechanisms)
* not model error

---

## Final Point

The mechanism was derived through reproducible structural analysis
and confirmed through real-world cases.

This indicates:

→ **low probability of structural error**  
→ **low probability of missing major mechanisms**  
→ **high alignment between model and actual system behavior**  

---
