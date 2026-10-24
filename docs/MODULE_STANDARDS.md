# Module Standards

Every module must use the same visible section order. Domain-specific calculators differ, but navigation, learning content, worked-solution formatting, validation, and source attribution must be consistent.

## Required visible section order

1. **Interactive tools** — one or more relevant calculators/analysis tools, with explicit units, input validation, error states, and no stale outputs after invalid calculations.
2. **Theory & formulas** — definitions, equations, variable/unit definitions, sign conventions, assumptions, and limits.
3. **Worked examples and source-derived problems** — source-derived questions selected from EE-29 / EE-32 only when the statement and data can be verified from the PDF page image. Every item must name the PDF, printed page, problem number, and whether wording is transcribed or lightly reformatted. Keep all given data and answer choices accurate. Never guess at illegible text or silently replace it with a generated problem. If no source problem can be confidently mapped to a module, say so explicitly.
4. **Worked solutions** — use the same sequence for every numerical solution: **Source and problem ID → Given → Find → Formula → Substitution → Step-by-step calculation → Final answer with units → Engineering interpretation**. Preserve source answer conventions, but independently check arithmetic and flag any apparent source discrepancy rather than silently changing the source.
5. **Supplementary practice** — clearly labeled as original/supplementary, not reviewer-derived. Include a mix of numerical and conceptual questions, with answers hidden until requested.
6. **Validation & references** — known regression cases, tested edge cases, assumptions/limitations, source page references, and an honest status (source inspection, static checks, numerical tests, and browser tests must not be conflated).

## Consistency requirements

- Every module must expose the seven sections above in this exact order and use the same navigation treatment and heading hierarchy.
- Reuse the same card, formula, input, result, error, and solution styles.
- Use the same labels and order for every numerical worked solution. Internal source IDs belong in documentation, not learner-facing headings.
- Keep a reviewer problem bank/map in documentation with: PDF filename, printed page, problem number, module destination, transcription confidence, checked answer, and integration status.
- Do not mark a PDF problem integrated until it is present in the correct module and its statement, data, source reference, and solution have been checked.
- Do not invent reviewer problem IDs, answer choices, page numbers, or claims of source provenance.
- Do not claim a calculation is browser-tested unless it has actually been executed in a browser.

## Numerical integrity

- Independently compute expected results rather than validating a result against the same implementation.
- Test nominal values, boundary cases, invalid values, zero values where physically valid, negative values where physically meaningful, and extreme values.
- Check unit conversions, complex arithmetic, sign conventions, singularities, division by zero, and non-finite results.
- Clear previous results after invalid inputs or failed calculations so stale answers are not mistaken for new results.
- Explicitly label approximations and educational-only results. These tools do not replace a verified engineering study.

## Shared UI

- Dark navy/slate base, cyan accents, amber cautions, consistent spacing and typography.
- Mobile-first responsive layout and accessible input labels.
- Consistent formula, substitution, steps, and final-answer blocks.
- Preserve domain-specific functionality while aligning the common structure.

## Source handling

Use supplied reviewer PDFs as source material. Inspect page images when text extraction is unavailable. Keep limited source-derived problem statements distinct from original examples and practice questions. When a scan is unclear, record it as pending verification instead of guessing.