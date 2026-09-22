# Contributing to the GraphRoots Specification

Thank you for your interest in contributing to GraphRoots. This document
explains how to propose changes and the licensing steps that every contribution
requires.

## Before you start

- Read the [Code of Conduct](CODE_OF_CONDUCT.md). Participation is expected to
  follow it.
- Read the [Governance](GOVERNANCE.md) document to understand how decisions are
  made.
- For anything beyond a small editorial fix, please open an issue first to
  discuss the idea before investing time in a pull request.

## The Contributor License Agreement (CLA) — required

GraphRoots is developed under the Open Web Foundation agreements. Before your
**first** contribution can be merged, you must sign the **OWF Contributor
License Agreement 1.0 (Copyright and Patent)**. This grants the copyright and
patent rights needed for the specification to be freely implementable. You sign
the CLA only once; it covers all of your future contributions.

There are two forms of the CLA. Which one applies depends on whether you
contribute as an individual or on behalf of an organization.

### Individual contributors

If you are contributing on your own behalf, signing is automatic and handled by
**CLA Assistant**:

1. Open your pull request as normal.
2. CLA Assistant comments on the PR with a link to the CLA and asks you to sign.
3. Sign by following the instructions in that comment. Your GitHub identity and
   the time of signing are recorded.
4. Once signed, the CLA status check turns green and your PR can be reviewed and
   merged. Future pull requests will not ask you again.

The individual CLA text is in
[`cla/OWF-CLA-1.0-individual.md`](cla/OWF-CLA-1.0-individual.md).

### Contributing on behalf of an organization (entity CLA)

If you are contributing as part of your employment, or your employer may hold
patent rights over your contributions, an **authorized representative** of your
organization must sign the **entity** CLA. A click-through signature by an
individual employee does not bind an employer's patents, so this is handled as a
signed document rather than through the bot.

See [`cla/OWF-CLA-1.0-entity.md`](cla/OWF-CLA-1.0-entity.md) and
[`cla/README.md`](cla/README.md) for how to submit a signed entity CLA. If you
are unsure which form applies to you, ask in your pull request or open an issue.

## How to contribute a change

1. **Fork** the repository and create a branch from `main`.
2. Make your changes. Keep each pull request focused on a single topic where
   possible.
3. Write clear commit messages describing the *what* and the *why*.
4. Open a pull request against `main`, fill in the pull request template, and
   link any related issue.
5. Sign the CLA when prompted (see above).
6. A maintainer reviews your change. Address feedback by pushing additional
   commits to your branch.

## Branching model

- `main` is the stable, default branch and reflects the current agreed state of
  the specification.
- Development happens on feature branches that land via reviewed pull requests.

## Editorial vs. normative changes

- *Editorial* changes (typos, formatting, clarifications that do not change
  meaning) are straightforward.
- *Normative* changes (anything that alters the requirements the specification
  defines) require discussion and explicit maintainer agreement, per the
  [governance process](GOVERNANCE.md).

## Questions

Open an issue or start a discussion. We are happy to help you land your first
contribution.
