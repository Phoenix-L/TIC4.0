# TIC4.0 / PAS 4000 reference repository

Reference hub for studying and applying TIC4.0 and PAS 4000:2026 in a small interoperability proof of concept.

## Start here

- [PAS 4000:2026 — original PDF](sources/BSI/PAS_4000_pas.pdf)
- [Source identity, provenance and checksums](sources/BSI/README.md)
- [TIC4.0 primary-source index](references/TIC40.md)
- [Review status and next research steps](REVIEW_STATUS.md)
- [RTG terminal operations — comparative research v0.1](references/operations/RTG_Operations_Comparative_Research_v0.1_2026-10-24.md) (provisional general operations model; owner review pending)

## Purpose and boundaries

Use this repository for source references, edition tracking and research notes. Project-specific operational analysis, mappings, adapters and demonstrations remain in the [VZJ POC working directory](https://github.com/Phoenix-L/VZJ/tree/research/tic40-pas4000-poc-stage-a-v0.1/06_Research/POC_TIC40_PAS4000) and [review PR #6](https://github.com/Phoenix-L/VZJ/pull/6). Access to that project repository may be restricted.

The official PAS text is the reference for its provisions. TIC4.0 publications provide domain terminology, models and explanatory guidance. Project decisions, extensions and synthetic examples must be identified separately.

**Current status:** The full PAS PDF is now available here. Identity, metadata and contents have been checked; a complete normative review and POC conformance assessment have not yet been completed. Earlier POC statements that the document had not been obtained describe the initial research state.

## Working conventions

- Preserve original source files byte-for-byte; record their origin, edition, acquisition date and hash.
- Distinguish publication content from research interpretation and POC design choices.
- Cite exact clauses and printed page numbers when reviewing PAS provisions. PDF-viewer page numbers differ from printed page numbers.
- Check requirements, commentary, notes and informative annexes separately; do not treat examples as requirements.
- Pin the actual TIC4.0 model artifacts and dictionary definitions used for a mapping, rather than relying only on mutable overview pages.
- Do not claim conformity or certification from successful parsing or a familiar message envelope.
- Use **unladen travel** and **laden travel** in original terminal-operation prose. Preserve exact source terminology, quotations and machine-readable identifiers.

## Copyright

PAS 4000:2026 is copyright The British Standards Institution 2026. Its notices are preserved in the original PDF. This repository does not grant an open-source licence to the PDF or other third-party material; publisher terms continue to apply. Official access and licensing enquiries should use [BSI Knowledge](https://knowledge.bsigroup.com/products/cargo-handling-facilities-digitalization-of-logistic-operations-specification).

## Bootstrap record

2026-10-19 — Repository initialized with the user-supplied PAS PDF, provenance/checksum record, TIC4.0 reference links and a research-status register. No adapter implementation or conformity result is included.
