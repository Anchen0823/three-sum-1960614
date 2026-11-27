# Deterministic word-RAM 3SUM at exponent 1.960614

**Cite the technical report and archived proof artifacts:** [DOI 10.5281/zenodo.23408567](https://doi.org/10.5281/zenodo.23408567) (Zenodo, version 1.0.0). This DOI identifies the report and its accompanying artifacts, not all future revisions of this repository.

The entry point is `Race.bound` in `Submission.lean`, with exact rational bound
980307/500000 and the unchanged official `EndStatement.ThreeSum` specification.
The official verifier supplies Lean 4.33.1 and its pinned Mathlib environment.

The machine proof extends c0ldzy17/three-sum-lean at commit
2b639655e07421b9ac743de9090459bab473a7c0 with expansion 232, the author-supplied
3sum_certificate_1p960614_v3 quartic and parameters, exact integer schedules,
and changed execution, cost and resource proofs. Codex assisted the extension.
Inherited Anthropic and other source credits, license headers and notices are
retained. See LICENSE and NOTICE. The independent fixed-model lower bound is
not used as an algorithmic premise.

Package preparation and a local Lean build do not establish site acceptance.
Comparator must independently compare the full theorem and definitions with
the official frozen statement, and the allowed-axiom audit must pass.