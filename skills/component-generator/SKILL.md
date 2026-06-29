---
name: component-generator
description: Generate reusable, token-driven, accessible frontend components using project conventions.
---

# Component Generator

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

USAGE EXAMPLES

REVIEW CHECKLIST
- Token usage
- Accessibility
- Responsive behavior
- Reuse
- Module compliance
```
