# Contributor License Agreements (CLA)

Every contribution to the GraphRoots Specification is made under the **OWF
Contributor License Agreement 1.0 (Copyright and Patent)**. This folder holds
the CLA texts. See [CONTRIBUTING.md](../CONTRIBUTING.md) for the contributor's
view of the process.

## Which CLA applies?

| You are… | CLA | How it's signed |
| --- | --- | --- |
| An individual contributing on your own behalf | [Individual CLA](OWF-CLA-1.0-individual.md) | Automatically, via **CLA Assistant**, on your first pull request |
| Contributing for an employer, or your employer may hold patent rights in your work | [Entity CLA](OWF-CLA-1.0-entity.md) | A signed document from an authorized representative (see below) |

If you are unsure, ask in your pull request or open an issue.

## Individual signing (automated)

Individual contributors do not need to do anything in advance. When you open
your first pull request, **CLA Assistant** comments with the CLA and asks you to
sign; once you sign, the CLA check passes and stays satisfied for future pull
requests.

The CLA text CLA Assistant presents is
[`OWF-CLA-1.0-individual.md`](OWF-CLA-1.0-individual.md). Keep that file and the
CLA Assistant configuration in sync.

## Entity signing (manual)

For organizations:

1. An authorized representative completes and signs
   [`OWF-CLA-1.0-entity.md`](OWF-CLA-1.0-entity.md).
2. Submit the signed agreement to the maintainers.
   <!-- TODO: specify the submission channel, e.g. email cla@graphroots.example
        with the signed PDF, or open a private issue. -->
3. Once received and recorded, contributions from that organization's listed
   contributors can be merged.

## Maintainer notes

- **CLA Assistant setup** (hosted service, `cla-assistant/cla-assistant`):
  configure at https://cla-assistant.io — sign in with the GitHub account that
  administers the `graphroots` organization, create a CLA linked to this
  repository, and point it at the individual CLA text. Signatures are stored in a
  GitHub Gist by the service.
- Keep a record (a private repo, gist, or folder) of signed **entity** CLAs.
- If you later prefer to keep signatures inside your own repositories rather than
  the hosted service, the `contributor-assistant/github-action` (formerly "CLA
  Assistant Lite") is a self-contained GitHub Action alternative that stores
  signatures as a file in a repo.
