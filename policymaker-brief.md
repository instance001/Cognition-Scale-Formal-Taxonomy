# The Cognition Scale — Policymaker Brief (v1.0)
## A Practical Framework for Regulating Human and Artificial Cognition

This brief defines a simple, enforceable, four-tier model for categorizing all
cognition systems used in public, commercial, or critical-infrastructure settings.

The Cognition Scale is substrate-agnostic and focuses on **risk, transparency,
and behavioral guarantees**, not hype or marketing claims.

---

# 1. The Four Cognition Classes

### Tier 1 — LCM (Large Cognition Model)
**Example:** Humans  
**Risk Profile:** Variable  
**Notes:**  
Humans are inherently unpredictable but self-governing.  
LCMs have full moral agency, emotions, situational wisdom, and ethical judgement.  
Regulation targets *behavior*, not internal architecture.

---

### Tier 2 — LLM (Large Language Model)
**Examples:** ChatGPT, Claude, Gemini, Llama  
**Risk Profile:** Medium–High  
**Key Risks:**
- hallucinations  
- persona drift  
- opacity (hidden internal state)  
- difficulty assigning accountability  
- unpredictable emergent behavior  

LLMs should never be deployed in environments requiring guaranteed correctness
without human oversight.

---

### Tier 3 — MCM (Modest Cognition Model)
**Example:** Janet  
**Risk Profile:** Low (Architecturally Contained)  
**Key Guarantees:**
- deterministic reasoning  
- transparent execution  
- explicit, auditable memory  
- growth controlled by human gatekeeping  
- strict limits on depth, recursion, and compositional logic  
- ambiguity rejection instead of hallucination  

MCMs are appropriate for:
- compliance checking  
- policy enforcement  
- verification tasks  
- safety-critical local systems  
- government & institutional audits  

They are **structurally safe** because they avoid the unpredictable features of LLMs.

---

### Tier 4 — SCM (Simple Cognition Model)
**Examples:** Rule engines, automation controllers  
**Risk Profile:** Very Low  
**Notes:**  
Reactive, non-reflective logic.  
Use-case: automation, embedded systems, local governance tools.

---

# 2. What This Framework Solves for Regulators

### ✔ Clear Classification  
Agencies can classify AI systems by architecture rather than marketing claims.

### ✔ Predictable Risk Levels  
LCMs → variable  
LLMs → unpredictable  
MCMs → bounded and inspectable  
SCMs → trivial risk

### ✔ Suitable for Legislation  
This scale can be referenced in:
- AI deployment guidelines  
- procurement standards  
- safety certification  
- compliance frameworks  
- risk assessments  

### ✔ Reduces Mislabeling  
Prevents companies from calling LLM systems “deterministic” or “safe-by-design.”

---

# 3. Key Recommendation

**Treat LLMs as high-risk statistical systems.**  
**Treat MCMs as low-risk deterministic tools.**  

This framework allows safe innovation without stifling high-performance models,
while giving regulators a simple way to classify systems at a glance.

---

# 4. License
AGPLv3 — regulators and organizations may freely use or adapt this framework.