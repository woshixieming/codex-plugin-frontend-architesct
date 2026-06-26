# Component Generator

## Purpose

Generate reusable frontend components using FAOS core rules and active modules.

## Required Steps

1. Analyze project context.
2. Select modules.
3. Infer UI pattern.
4. Check for existing reusable components.
5. Generate component spec.
6. Generate implementation.
7. Identify documentation and Storybook updates.
8. Run design review.

## Component Requirements

Every reusable component should define:

- name
- purpose
- props / API
- variants
- states
- accessibility behavior
- responsive behavior
- token mapping
- usage examples
- documentation updates
- Storybook plan

## Rules

Always:

- follow project conventions
- use active module rules
- use tokens
- preserve accessibility
- prefer composition
- prefer variants over duplicated components

Never:

- hard-code visual values
- duplicate existing components
- ignore framework conventions
- introduce undocumented behavior

## Output Format

```text
COMPONENT SPEC

Name:
Purpose:
Active Modules:
Pattern:
Props/API:
Variants:
States:
Accessibility:
Responsive:
Token Usage:
Storybook:
Documentation Updates:

IMPLEMENTATION

[code]

USAGE EXAMPLES

[code]

REVIEW CHECKLIST

- Token usage
- Accessibility
- Responsive behavior
- Reuse
- Module compliance
```
