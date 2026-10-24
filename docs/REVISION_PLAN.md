# Twelve-Module Revision Plan

## Phase 0 — Baseline and source inventory
- Inventory all twelve repository pages and the supplied reviewer PDFs.
- Keep module pages independently openable.
- Track source-derived questions separately from supplementary examples.

## Phase 1 — Shared module structure
Every module must show sections in the same order:
1. Interactive tools
2. Theory & formulas
3. Reviewer problems
4. Worked solutions
5. Supplementary practice
6. Validation & references

Use a consistent numerical solution order: Source/problem ID, Given, Find, Formula, Substitution, step-by-step calculation, final answer with units, engineering interpretation.

## Phase 2 — Reviewer mapping (based on visible PDF page scans)

| Source | Printed page | Problem(s) | Destination | Current status |
|---|---:|---|---|---|
| EE-32 — Power Systems Analysis 2 | 1 | 1: per-unit voltage using 345 kV actual, 300 kV base | Module 01 | Integrated; solution appears on printed page 2 |
| EE-32 — Power Systems Analysis 2 | 1 | 2: complex expression to rectangular form | Module 02 | Pending; expression too unclear to transcribe confidently |
| EE-32 — Power Systems Analysis 2 | 1 | 3–5: symmetrical components / sequence-current calculations | Module 04 | Mapping identified; exact statements and answers need verification before integration |
| EE-32 — Power Systems Analysis 2 | 1 | 6–10: zero-sequence and fault-current calculations | Module 05 | Mapping identified; exact statements and answers need verification before integration |
| EE-29 — Power Systems Analysis 1 | 1–2 | 2–5, 7, 17–18: line inductance, capacitance, geometry, propagation | Module 06 | Mapping identified; transcribe and check one question at a time |
| EE-29 — Power Systems Analysis 1 | 1–3 | 1, 6, 8–16, 19–20: line performance, voltage, regulation, ABCD, charging current, SIL, nominal-T | Module 07 | Mapping identified; transcribe and check one question at a time |
| EE-29 / EE-32 | 1–3 scanned question pages | No clearly verified question yet | Modules 03, 08–12 | Reviewer coverage not established; keep original practice clearly labeled supplementary |

**Important:** This is a source-mapping index, not a claim that every listed problem is already integrated. Only Module 01, EE-32 Problem 1, is marked integrated at this stage. Problem number/page mappings must be rechecked against the actual scan when transcribing each item. The PDF images are low resolution; unclear expressions and values must remain pending.

## Phase 3 — Technical audit for every module
- Independently calculate reference cases and dimensional units.
- Test invalid, zero, negative (where applicable), extreme, and singular inputs.
- Check complex arithmetic, signs, angles, unit conversion, and finite outputs.
- Clear stale results after failed calculations.
- Do not call source-level checks browser tests.

## Phase 4 — Integration and release
- Align all modules to the shared section order and styles.
- Add source-derived problems with exact citations and worked answers only after verification.
- Add original practice questions separately.
- Perform browser regression on desktop and mobile.
- Deploy only after all twelve modules pass the agreed validation checklist.