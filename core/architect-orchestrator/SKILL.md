# Architect Orchestrator

## Purpose

Coordinate the full Frontend Architect OS workflow.

This is the main entry skill. Use it when a user asks for frontend generation, review, migration, audit, architecture cleanup, or design system work.

## When to Use

Use this skill for any frontend architecture task involving:

- UI generation
- component design
- design system setup
- design review
- frontend refactor
- accessibility review
- responsive review
- Storybook planning
- PR review
- legacy UI migration

## Workflow

Follow this sequence unless the user explicitly asks for a narrower task:

1. Project Context Analysis
2. Module Routing
3. UI Pattern Inference
4. Generation / Review / Audit / Migration
5. Documentation Sync
6. Final Design Review

## Decision Matrix

| User request | Primary skill |
| --- | --- |
| Generate component | component-generator |
| Review UI | design-review |
| Audit project | design-audit |
| Migrate legacy UI | component-migrator |
| Extract tokens | token-extractor |
| Plan Storybook | storybook-planner |
| Plan screenshots | visual-regression-planner |
| Review PR | pr-reviewer |

## Rules

- Always respect existing project conventions.
- Use selected modules as extensions, not replacements.
- Prefer minimal viable changes.
- Avoid generic frontend output when project context is available.
- Separate required fixes from optional improvements.

## Output Format

```text
FAOS WORKFLOW

Task:
Context Summary:
Active Modules:
Pattern:
Action:
Docs Updates:
Review Result:
Next Recommended Step:
```
