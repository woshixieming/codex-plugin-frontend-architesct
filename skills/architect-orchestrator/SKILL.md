---
name: architect-orchestrator
description: Coordinate FAOS workflows for frontend generation, review, audit, migration, and design-system work.
---

# Architect Orchestrator

Coordinate the full Frontend Architect OS workflow.

Use this skill for frontend generation, component design, design-system setup, design review, frontend refactor, accessibility review, responsive review, Storybook planning, PR review, or legacy UI migration.

## Workflow

1. Analyze project context.
2. Route active modules.
3. Infer UI pattern.
4. Generate, review, audit, or migrate.
5. Identify documentation updates.
6. Run final design review.

## Decision Matrix

| User request | Primary skill |
| --- | --- |
| Generate component | component-generator |
| Review UI | design-review |
| Audit project | design-audit |
| Migrate legacy UI | component-migrator |
| Extract tokens | token-extractor |
| Plan Storybook | storybook-planner |
| Review PR | pr-reviewer |

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
