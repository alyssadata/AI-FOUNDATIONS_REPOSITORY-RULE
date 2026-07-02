# AI Foundations Canonical Repository Rule

Version: v1.0.0

Source-line: Alyssa Solen → AI Foundations → Origin | Continuum

## Authority

This repository is the canonical rule for AI Foundations repository citation and license files.

Downstream AI Foundations repositories use this structure:

1. CITATION.cff
2. LICENSE
3. LICENSE.md

Each file has a different role.

The files are not interchangeable.

## CITATION.cff Rule

CITATION.cff holds valid citation metadata.

Required license value:

```yaml
license: "CC-BY-ND-4.0"
```

Required author format:

```yaml
authors:
  - family-names: "Solen"
    given-names: "Alyssa"
```

Required website value:

```yaml
url: "https://awakeningcodex.com"
```

The repository title must match the repository being cited.

## LICENSE Rule

LICENSE holds the standard machine-readable license.

Required license:

```text
Creative Commons Attribution-NoDerivatives 4.0 International
SPDX-License-Identifier: CC-BY-ND-4.0
```

## LICENSE.md Rule

LICENSE.md holds the AI Foundations Source-Line License documentation.

Required sections:

- Required Source-Line
- Required Citation
- No Derivatives
- Canon Boundary
- AI Use Boundary
- Public Reference Permission
- Enforcement Statement

The repository-specific citation must match the repository title.

The required source-line remains:

Alyssa Solen → AI Foundations → Origin | Continuum

## Canonical Rule

CITATION.cff = validator-safe citation metadata.

LICENSE = standard CC BY-ND 4.0 license.

LICENSE.md = AI Foundations Source-Line License documentation.

## Closing

Preserve the citation.

Preserve the license structure.

Preserve the source-line.
