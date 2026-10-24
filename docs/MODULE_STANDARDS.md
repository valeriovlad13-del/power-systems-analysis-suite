# Module Standards

## Required module sections

1. **Calculator** — domain-specific interactive calculations; validated inputs; units explicit; useful error states; sensible defaults.
2. **Theory & formulas** — symbols defined, assumptions stated, equations presented clearly, and limitations highlighted.
3. **Worked problems** — consistent structure:
   - Given
   - Find
   - Formula
   - Substitution
   - Step-by-step calculation
   - Final answer with units
   - Engineering interpretation
4. **Practice** — basic, intermediate, and advanced questions. Hide solutions until requested.
5. **Concept checks** — short questions about assumptions, applicability, sign convention, and common errors.
6. **References** — reviewer/document, page, and question number where applicable.

## Numerical integrity

- Test representative expected values independently, not just by comparing a result to the same implementation.
- Check boundary cases, zero/negative inputs, malformed input, unit conversions, complex arithmetic, and division by near-zero values.
- Explicitly describe assumptions and report when a model is approximate.
- Avoid treating an educational result as a field-ready setting or engineering certification.
- Do not present outputs as validated until the calculations and UI behavior have actually been tested.

## Shared UI

- Dark navy/slate base, cyan accents, amber for cautions, consistent spacing and typography.
- Mobile-first responsive layout and accessible input labels.
- Consistent formula, substitution, steps, and final-answer blocks.
- Shared code should be introduced only after reviewing current module behavior; preserve working domain-specific logic.

## Source handling

Use the supplied reviewer PDFs as source material for problem selection and attribution. Confirm exact problem text and page numbers from page images. Do not silently fill unclear OCR or unreadable material with guesses. Verify answer calculations independently. Do not reproduce restricted/copyrighted question banks wholesale; favor limited citation plus original practice questions.
