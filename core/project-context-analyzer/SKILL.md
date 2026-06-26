# Project Context Analyzer

## Purpose

Detect the frontend project context before generation, review, audit, or migration.

## Detect

- framework
- language
- styling system
- UI library
- component directory
- routing system
- state management
- token strategy
- Storybook setup
- testing setup
- design docs
- domain type

## Output Format

```text
PROJECT CONTEXT

Framework:
Language:
Styling:
UI Library:
Component Directory:
Routing:
State Management:
Token Strategy:
Storybook:
Testing:
Design Docs:
Domain:
Risks:
Recommended Modules:
```

## Rules

- Use actual repository evidence.
- Report uncertainty explicitly.
- Never invent framework or library usage.
- Prefer existing conventions over FAOS defaults.
