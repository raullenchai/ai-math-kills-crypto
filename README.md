# Does AI Math Kill Crypto?

An analysis of selected OpenAI Math results and their implications for blockchain cryptography: secp256k1, ECDSA, Schnorr, BLS, KZG and related proof systems.

**Read the interactive report:** [Open the report](https://raullenchai.github.io/ai-math-kills-crypto/)

## Finding

The eight selected result families **do not establish a practical, end-to-end attack-cost reduction against the blockchain targets examined**. Some stated mathematical advances are substantial; a usable cryptanalytic reduction, a competitive target-sized algorithm or both remain missing.

This does not establish that a break is far away. One mathematical method could close several gaps at once. Shared groups, reusable precomputation and a shared KZG setup can amplify an attack. The number of missing steps is not a measure of remaining research effort, time or attack probability.

## What is included

- A unified interactive map from mathematical results through missing attack bridges to conditional blockchain consequences.
- Old/new algorithm comparisons, distinguishing solved mathematical tasks from unsolved cryptographic targets.
- Quantitative resource tables separating full-attack work from illustrative asymptotic function values.
- Nonlinear cascade analysis, primary references and a scoped review record.
- The complete English HTML report and two English summary figures.

## Scope and source version

We conducted a focused review of **8 selected result families / 10 manuscripts**: **#142, #029, #107, #103, #109, #279, #002 and #030**. The three #107 manuscripts account for the difference. For #002 and #030, the review is limited to abstracts and main-theorem context. This is not an exhaustive audit of the collection.

The source snapshot is commit [`adc7f1241b42e322a6451854ab7e4b4c146bf78a`](https://github.com/openai/math/tree/adc7f1241b42e322a6451854ab7e4b4c146bf78a), examined October 7, 2026. Its catalogue contains 722 manuscripts across 372 families.

A publication check on October 8 found that the live catalogue now contains 719 manuscripts. The [official revision history](https://github.com/openai/math/blob/main/history.md) records three withdrawals outside the eight selected families and other repairs, including removal of an obsolete introductory citation in #002. The report retains its pinned source snapshot; it is not a new audit of every revision.

Attack implications are conditional on the stated mathematical theorems and the specified cryptographic instances. Original mathematical proofs were not verified. The English source-statement and arithmetic analysis underwent three rounds of Claude Opus 5.5 review, with displayed arithmetic separately recomputed. Model agreement is not a correctness certificate. Subsequent conditional cascade analysis should not be read as a demonstrated attack.

## Files

| File | Contents |
| --- | --- |
| [index.html](index.html) | Complete English report, interactive map, tables and scoped review record |
| [Attack overview](assets/figure-1-attack-bridges.png) | Candidate families, missing bridges and conditional consequences |
| [Quantitative overview](assets/figure-2-quantitative.png) | Full-target work versus normalized mathematical examples |

The HTML report is standalone: download the file and open it in a modern browser. The live website is served by GitHub Pages and has no scheduled document expiry.

## Expert feedback

Corrections and concrete attack mechanisms are welcome in [Issues](https://github.com/raullenchai/ai-math-kills-crypto/issues). Useful submissions identify:

1. The result and exact theorem or proof tool.
2. The target curve, subgroup, SRS or cryptographic instance.
3. An effective reduction or algorithm, including representation and size growth.
4. End-to-end time, memory, precomputation, hardware assumptions and finite-size costs.
5. The specific protocol consequences and exploitation conditions.

This repository is an independent analysis, not an official OpenAI publication.
