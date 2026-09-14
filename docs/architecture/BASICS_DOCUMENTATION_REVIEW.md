<!-- SPDX-License-Identifier: Apache-2.0 -->

# Basics documentation merge review

Date: 2026-09-14. Base: `f80c812284150869f94cfe4a71992dbe4cd7c194`.

## Scope and decision

Bounded documentation update: root README and two new reading/review pages. Recommendation: merge this documentation scope after Operator approval, provided the PR head remains the reviewed revision. No blocking finding remains in the checked scope. This is not independent external review, runtime approval, or a claim of full canonical-source fidelity.

The main issue found was an inventory mismatch: the original README described schemas, validators and runnable demonstrations as provided surfaces, while tracked files contain only documentation, artwork and LICENSE. The revised README labels those component types as future adoption goals and routes runnable-tool users to NOW.

## Checks

- Tracked-file inventory inspected: no implementation, automated test suite or CI workflow exists in the reviewed base.
- Current Hybrid source identity and bounded read coverage are stated in the [reading guide](HYBRID_BASICS_GUIDE.md). Current guidance does not relabel every older source as newly reviewed.
- Changed Markdown relative file links checked for target existence. External NOW guide and Public repository destinations checked through GitHub. This is not a comprehensive external-link or heading-anchor audit.
- New and edited Markdown retain Apache-2.0 identifiers. Root LICENSE remains byte-preserved; no license policy migration is performed.
- Historical FAQ/architecture sources, image/provenance, LICENSE and tags remain unchanged. The change set contains no runtime, EDP instrument, private source, or experimental execution.
- Whitespace check performed on the staged change set. There are no software tests to run in this repository; no test-pass count is invented.

## What this does not certify

No claims of native model-zero physiology, actual schema validation, scientific proof, model trials, checkpoint recovery, or organism-wide integration arise from these pages. OI H1–H7 remain hypotheses. The preserved earlier source matrix and v1.5 orientation retain their original text and time-specific labels; the root entry and new guide provide current context without rewriting that lineage.

NOW carries active applied development. Basics remains a maintained reading foundation, not an automatic mirror of NOW or the full organism. Future executable contributions require separate implementation, licensing and validation review.
