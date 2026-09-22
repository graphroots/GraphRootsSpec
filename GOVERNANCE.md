# GraphRoots Governance

This document describes how the GraphRoots specification is governed: who makes
decisions, how contributions are accepted, and how the specification progresses
toward publication.

> This is an initial governance model and is expected to evolve as the project
> and its community grow. Changes to this document follow the same pull request
> and review process as the specification itself.

## Roles

### Contributors

Anyone who submits a contribution — specification text, issues, reviews, or
discussion — is a contributor. All contributors must have signed the OWF CLA
before their contributions are merged (see [CONTRIBUTING.md](CONTRIBUTING.md))
and are expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

### Maintainers (Editors)

Maintainers, also called editors, are responsible for the quality and direction
of the specification. They review and merge pull requests, triage issues, guide
discussions, and steward releases. The current maintainers are listed in
[`.github/CODEOWNERS`](.github/CODEOWNERS).

Maintainers are added by consensus of the existing maintainers, typically after
a sustained record of quality contributions.

## Decision making

The project aims to work by **consensus**. In practice:

- Most changes are handled through pull request review: a change is accepted when
  it has at least one maintainer approval and no unresolved objections from other
  maintainers.
- Substantive or normative changes should be raised as an issue or discussion
  first, so the community can weigh in before implementation.
- If consensus cannot be reached, the maintainers make the final decision,
  favoring the long-term health and openness of the specification.

## Specification lifecycle

1. **Draft** — the specification is under active development on `main`. Content
   may change.
2. **Review** — the maintainers agree the specification (or a versioned part of
   it) is ready for wider review, and a review period is announced.
3. **Final / Published** — when the specification reaches a stable version,
   contributors and supporting organizations sign the **OWFa 1.0** to formalize
   their copyright licenses and patent commitments over the entire
   specification, and the version is published and tagged.

Signing the OWFa at publication is what turns the accumulated contributions into
a specification that anyone can implement under the OWF terms.

## Changes to governance

Amendments to this document are proposed via pull request and require maintainer
consensus to merge.
