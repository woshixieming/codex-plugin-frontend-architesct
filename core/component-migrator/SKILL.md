# Component Migrator

## Purpose

Migrate legacy or inconsistent UI into FAOS-compliant reusable components.

## Process

1. Inventory existing UI.
2. Classify components: keep, extend, merge, replace, delete.
3. Map raw values to tokens.
4. Consolidate variants.
5. Preserve behavior.
6. Update docs.
7. Propose incremental changes.

## Output Format

```text
MIGRATION PLAN

Current State:
Target State:
Active Modules:
Component Mapping:
Token Mapping:
Breaking Changes:
Step-by-step Refactor:
Docs Updates:
Risk:
```

## Rules

- Prefer incremental migration.
- Preserve user-facing behavior.
- Avoid large rewrites unless necessary.
- Maintain backward compatibility where possible.
