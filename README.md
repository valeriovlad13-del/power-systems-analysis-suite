# Power Systems Analysis Suite

Interactive educational tools for studying power systems analysis. The project is being developed as a collection of standalone modules with consistent styling, documented assumptions, worked examples, practice problems, and regression-tested calculations.

> **Engineering disclaimer:** This is an educational project, not a substitute for validated engineering software or a qualified engineering study. Do not use outputs alone to set or operate real power-system equipment.

## Development status

The repository has just been initialized. The 12 modules built as standalone prototypes in the development conversation have not yet been imported into this repository. The existing `index.html` is an empty placeholder and is intentionally retained until the suite architecture is ready.

## Planned modules

1. Per-Unit System & Base Impedance
2. Complex Phasors & Network Conversion
3. Three-Phase Power & Capacitor Sizing
4. Symmetrical Components
5. Fault Analysis
6. Transmission Line Parameters
7. Transmission Line Performance & ABCD Parameters
8. Ybus Formation & Load Flow Analysis
9. Economic Dispatch & Plant Performance
10. Synchronous Machines & Power-System Stability
11. Distribution Design & Transformer Sizing
12. Relay Protection & Fault Coordination

## Module learning format

Each module should aim to include:

- **Calculator(s):** validated inputs, clear units, input checks, and meaningful error states.
- **Theory & formulas:** notation, assumptions, and boundaries of applicability.
- **Worked problems:** Given, Find, Formula, Substitution, Calculation, Final Answer with Units, and Engineering Interpretation.
- **Practice problems:** a progressive difficulty range, with solutions hidden until requested.
- **Concept checks:** common mistakes and short questions that test understanding.
- **References:** cite the uploaded course reviewers by document, page, and problem number when a problem is sourced from them. Independently verify calculations before publishing answers.

For topics not covered in the uploaded reviewers, mark exercises as supplementary rather than attributing them to the source.

## Planned structure

```text
assets/
  css/shared.css
  js/shared.js
modules/
  01-per-unit/
  02-complex-phasors/
  03-three-phase-power/
  04-symmetrical-components/
  05-fault-analysis/
  06-transmission-line-parameters/
  07-transmission-line-performance/
  08-ybus-load-flow/
  09-economic-dispatch/
  10-synchronous-machines/
  11-distribution-transformers/
  12-relay-protection/
practice/
  power-systems-analysis-1/
  power-systems-analysis-2/
tests/
  calculations/
  regression/
```

This is a target structure, not a claim that these directories or tests already exist. Preserve working prototype code during migration and validate each calculator against independently computed reference cases.

## Development sequence

1. Inventory and migrate the current prototypes without losing their calculations.
2. Audit equations, units, sign conventions, boundary cases, and numerical results.
3. Establish shared styling and a consistent worked-solution presentation.
4. Add source-grounded problems from the two course reviewers and verify each answer.
5. Add automated calculation regression tests and browser checks where possible.
6. Build the master dashboard only after the modules are stable.

## Reviewer source attribution

The two provided reviewer PDFs are referred to during development as:

- *EE-29 Power Systems Analysis 1* — page/problem references should be confirmed against the original page images.
- *EE-32 Power Systems Analysis 2* — page/problem references should be confirmed against the original page images.

The repository should contain only material that may appropriately be redistributed. When the source is copyrighted or marked for restricted distribution, prefer original, paraphrased practice questions with citations rather than reproducing full question sets verbatim.

## License

No license has been selected yet. Until a license is added, do not assume others have permission to reuse or redistribute the code.
