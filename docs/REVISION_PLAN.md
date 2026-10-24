# Twelve-Module Revision Plan

## Phase 0 — Establish baseline
- Inventory repository files and currently available standalone prototypes.
- Preserve each prototype before structural changes.
- Record module-specific calculators, current formulas, input/output conventions, and known issues.
- Build a migration checklist; do not mark an audit complete without actual tests.

## Phase 1 — Shared foundation
- Add shared CSS and small shared JS helpers only after comparing modules.
- Define design tokens, common worked-example layout, solution steps, units, error messages, tabs/navigation, and accessibility conventions.
- Keep each module independently openable.

## Phase 2 — Module-by-module audit
For every module:
- Inspect formulas, dimensional consistency, sign conventions, and assumptions.
- Independently calculate reference cases.
- Test input validation, edge cases, and output formatting.
- Fix known issues and document unsupported conditions.
- Add source-relevant worked problems and original supplementary exercises.
- Record regression tests and test status.

## Phase 3 — Review problem mapping
- Module 1: per-unit and base impedance.
- Module 2: complex arithmetic, phasors, impedance/network transformations.
- Module 3: AC power, three-phase relationships, power-factor correction.
- Module 4: symmetrical components and sequence conversion.
- Module 5: symmetrical fault networks and fault-current calculations.
- Module 6: conductor resistance, GMD/GMR, inductance, capacitance, charging current.
- Module 7: ABCD models, short/medium/long lines, sending/receiving end, regulation and efficiency.
- Module 8: Ybus and load flow; supplementary problems may be needed if reviewer coverage is limited.
- Module 9: economic dispatch and plant factors; supplementary problems may be needed.
- Module 10: synchronous machines and stability; supplementary problems may be needed.
- Module 11: distribution and transformer sizing; supplementary problems may be needed.
- Module 12: CT ratios, pickup, IEC inverse-time curves, grading/coordination; reviewer coverage may be limited, so label original questions supplementary.

Confirm exact source question/page mapping from the source PDF images before publishing.

## Phase 4 — Integration
- Build the dashboard only after module structures and test conventions stabilize.
- Add module cards, progress/accessibility and consistent navigation.
- Run cross-module regression and mobile/desktop checks.
