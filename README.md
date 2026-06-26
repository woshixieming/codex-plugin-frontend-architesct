# Frontend Architect OS

Frontend Architect OS, abbreviated as **FAOS**, is a Codex Desktop plugin for frontend architecture governance.

It helps Codex work like a frontend architect instead of a one-off code generator.

## What FAOS Does

FAOS provides structured guidance for:

- frontend design systems
- design tokens
- reusable component generation
- UI pattern inference
- accessibility review
- responsive design review
- Storybook planning
- visual regression planning
- pull request review
- legacy UI migration
- framework-specific frontend conventions

## Philosophy

Most AI-generated frontend code fails because it lacks architectural memory.

FAOS solves this by separating:

```text
Core rules
  ↓
Framework modules
  ↓
UI library modules
  ↓
Domain modules
  ↓
Reusable templates
  ↓
Reference resources
```

The core remains stable. Framework-specific and domain-specific rules live in modules.

## Directory Structure

```text
frontend-architect-os/
├── plugin.json
├── README.md
├── LICENSE
├── core/
│   ├── architect-orchestrator/
│   ├── project-context-analyzer/
│   ├── module-router/
│   ├── ui-pattern-infer/
│   ├── component-generator/
│   ├── design-review/
│   ├── design-audit/
│   ├── token-extractor/
│   ├── component-migrator/
│   ├── storybook-planner/
│   ├── visual-regression-planner/
│   └── pr-reviewer/
├── modules/
│   ├── react/
│   ├── vue2/
│   ├── vue3/
│   ├── tailwind/
│   ├── ant-design/
│   ├── element-plus/
│   ├── dashboard/
│   └── mobile-h5/
├── templates/
│   ├── component-spec.md
│   ├── component-doc.md
│   ├── token-doc.md
│   ├── storybook-plan.md
│   ├── audit-report.md
│   └── pr-review.md
├── resources/
│   ├── design-principles.md
│   ├── component-patterns.md
│   ├── accessibility-checklist.md
│   ├── responsive-checklist.md
│   └── token-taxonomy.md
└── docs/
    ├── installation.md
    ├── usage.md
    ├── architecture.md
    ├── module-authoring.md
    └── roadmap.md
```

## Installation

Copy this folder into:

```text
~/.codex/plugins/frontend-architect-os/
```

Then restart Codex Desktop if needed.

## Daily Workflow

Use this prompt in Codex:

```text
Use Frontend Architect OS.
Analyze the project context, select the right modules, infer the UI pattern, generate the implementation, and run a design review.
```

## Common Workflows

### Generate a component

```text
Use FAOS to generate a reusable UserCard component.
Follow existing project conventions, use tokens, include accessibility and responsive behavior, and produce a review checklist.
```

### Review frontend code

```text
Use FAOS to review the current frontend changes for token usage, component reuse, accessibility, responsive behavior, documentation drift, and Storybook coverage.
```

### Migrate legacy UI

```text
Use FAOS to audit the current UI, extract token candidates, propose component consolidation, and create an incremental migration plan.
```

## Project Status

FAOS is currently a prompt-first Codex plugin architecture.

It is designed to be open-source friendly and extensible.
