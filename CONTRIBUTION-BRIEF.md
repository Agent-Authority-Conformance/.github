# Contribution Brief

The lab records test cases and run results against a stated source. Contributions should be reproducible, have explicit source and provenance, and claim no more than the evidence supports.

Before adding a fixture, runner or run record, answer:

**Source.** What exact source and revision define the expected behavior? Mark draft, proposed or implementation-defined sources clearly.

**Case.** What input is tested, and what outcome is expected? If the source does not determine one, say so.

**Controls.** For a new case family, include a positive control. Negative cases should isolate one named defect where practical.

**Failure stage.** If rejection is expected, what stage is the case intended to exercise?

**Indeterminate cases.** If the available evidence cannot establish a claim, record it as indeterminate or unsupported. Missing evidence for a claim is not a pass for that claim.

**Provenance.** Record who authored the vectors, who ran them, and the implementation and revision used. For published runs, preserve the applicable `author-produced` / `independent` label. Mixed provenance stays explicit.

**Boundary.** State what the result does not establish. A run records observed behavior for the tested implementation and revision, not a verdict on the implementation.

Read the source on its own terms. Do not give a statement more normative force than the source gives it.

Check existing issues and pull requests before starting a new case family.
