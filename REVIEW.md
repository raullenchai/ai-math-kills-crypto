# Repository review record

## Scope

On October 8, 2026, Claude CLI using **`claude-opus-5-5`** reviewed the repository at initial English-only commit `c4f4228d4e64ef9bbd2a4624361962e7f25c060f`.

The repository audit covered the README, the complete extracted static text of `index.html`, its JavaScript and runtime route/resource data, and both actual PNG figures. The reviewer read abstracts, main theorems and introductory context from the ten selected manuscript extracts, plus targeted passages on #142's promises, #109's cutoff and #107's finite-exception theorem. No manuscript was read in full and no mathematical proof was verified.

The reviewer also checked the recorded arithmetic, source-version notes and selected passages from the downloaded Ethereum specifications. Some external references and protocol details were not independently audited in that round. Model review is not proof certification, a target-sized benchmark, or evidence that no unrecognized attack exists.

## First audit: three blockers identified

| Finding | Correction |
| --- | --- |
| The historical round-3 verdict could be read as covering the later combined page, executive/cascade section, README and PNG figures. | Explicitly limited those three rounds to two earlier standalone reports and separated the repository audit from that historical record. |
| #109's primary gap was described as implementation/measurement, suggesting an existing practical gain waiting to be measured. | Replaced that classification with the absence of a competitive finite-size mechanism. The huge cutoff and schoolbook fallback are explicit; routine benchmarking cannot supply a useful algorithm. D3–D4 is a qualitative judgment about further algorithmic work, not a measured distance to an attack. |
| #107 used a dense exponent above 2 as an overly broad reason to dismiss gains, and its static/runtime descriptions differed. | Stated that finite-size comparison depends on dimension, sparsity, epsilon, constants, crossover and storage. Domain applicability and missing competitive implementations are the relevant constraints. Unified the static/runtime conclusion: no full-attack gain mechanism is established. |

The corrections retain a bounded evidence claim: no competitive end-to-end attack gain has been demonstrated. They do not turn asymptotic expression values into finite-size algorithm-performance guarantees, or rule out future sparse, dense or hybrid algorithms.

## Additional clarity changes

- Added the polynomial-time qualifier to the #103 figure and summary card.
- Added the every-fixed-field comparison to the quantitative figure, explicitly as a normalized function ratio, not an attack speedup.
- Made the hypothetical #142-to-RSA bridge consistent between the unified map and route selector; the added edge is an unestablished reduction.
- Documented the exploratory candidate-selection method and the unreviewed proof dependency chain beyond #029.
- Pinned the validator-specification reference and clarified the unreviewed reference-only revisions in the source collection.

## Follow-up review

On October 8, 2026 the same reviewer re-read the working-tree README.md and REVIEW.md, the regenerated visible-text extract of index.html, script-0.js, the runtime node, edge and resource data, and both PNG figures. It confirmed that the three blockers were corrected and found no new numerical or logical blocker in the report; it requested one wording correction in this record, since applied. It did not re-read the manuscripts, render the page, audit external references or verify any proof. This is not a correctness certificate. The first audit was not a clean pass.

## Separate checks by the author

- Recomputed eight numerical examples using 100-digit Decimal arithmetic.
- Checked the HTML's current map/table structure, functioning controls, page errors and diagram-label bounds in a browser.
- Checked published text and embedded textual downloads for Chinese characters.
- Checked the GitHub Pages response against the repository HTML and confirmed that the removed translated page returns 404.

These checks validate arithmetic reproduction, artifact consistency and presentation. They do not establish the validity of the original proofs, a probability of a future break or a remaining research timeline.
