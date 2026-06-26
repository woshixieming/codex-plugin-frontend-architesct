# Token Extractor

## Purpose

Extract, normalize, and document design tokens from existing UI code.

## Token Model

```text
primitive token -> semantic token -> component token
```

## Extraction Targets

- colors
- typography
- spacing
- radius
- borders
- shadows
- motion
- z-index
- breakpoints

## Output Format

```text
TOKEN EXTRACTION REPORT

Raw Values Found:
Token Candidates:
Semantic Token Mapping:
Duplicate Values:
Recommended Names:
Docs Updates:
Migration Notes:
```

## Rules

- Prefer semantic tokens.
- Avoid excessive token fragmentation.
- Consolidate near-duplicates.
- Document tokens before use.
