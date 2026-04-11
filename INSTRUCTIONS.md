# AI Capability Studio — User Instructions

---
### 2. What This Tool Does
This infrastructure tool provides an authoring environment for defining, structuring, and distributing organizational capability frameworks. It serves as the master repository where the definitions for "Awareness", "Ethics", and other domains are maintained before they are consumed by diagnostic tools.

---
### 3. Role in the Ecosystem
- **Phase:** Phase 5 — Infrastructure
- **Role:** Infrastructure for authoring and distributing capability frameworks.
- **Reference:** [../SYSTEM_OVERVIEW.md](../SYSTEM_OVERVIEW.md)

---
### 4. When to Use This Tool
- When initially establishing an organization's specific AI framework definitions.
- When updating the qualitative descriptions of what constitutes "Strong" vs "Low" capability.
- To export a unified capability schema that updates the rest of the Phase 3 tools.

---
### 5. Inputs
- Configuration of qualitative text, domain properties, and diagnostic thresholds via the administrative interface.

---
### 6. How to Use (Step-by-Step)
1. Navigate to the core framework definition section.
2. Define or edit the top-level domains (e.g., Awareness, Co-agency).
3. Specify the qualitative statements defining each maturity band (Low, Developing, Strong).
4. Update associated discussion prompts or diagnostic risk flags.
5. Export the finalized framework as a structured configuration payload.

---
### 7. Key Outputs
- A master JSON schema document representing the institutional standard for capability.
- Standardized rubrics for consumption by downstream assessment tools.

---
### 8. How It Connects to Other Tools
- **Upstream:** None (it is a foundational authoring tool).
- **Downstream:** The master schema dictates the structure of the **Capability Assessment**, **Capability Dashboard**, and **Gaps & Risk** tools.

---
### 9. Limitations
- Does not assess anything itself; it is only an authoring environment for the rubrics.
- Changes made here will aggressively impact how downstream tools interpret data.

---
### 10. Tips
- Treat the output of this tool as an institutional policy document. Do not distribute a new schema to the broader ecosystem without formal approval.
