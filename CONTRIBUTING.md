# Contributing

Before submitting a fixture, runner or run record, make sure a reviewer can answer:

- what exact source and revision the case is checked against
- what the positive control is and what each negative case changes
- what outcome and failure stage are expected, including indeterminate or unsupported cases
- who authored the vectors, who ran them, which implementation and revision were used, and the applicable `author-produced` / `independent` label
- what the result does not establish

For a new case family, open or link an issue first so the source and scope can be checked before work goes into vectors.

Every commit under these default guidelines needs a DCO sign-off (`git commit -s`). A repository with its own CONTRIBUTING file follows that file instead.

Contributions are accepted under the repository's license.

See the [Contribution Brief](https://github.com/Agent-Authority-Conformance/.github/blob/main/CONTRIBUTION-BRIEF.md) for the full reasoning.
