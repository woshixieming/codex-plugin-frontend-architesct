# React Module

## Purpose

Apply React / Next.js frontend architecture conventions.

## Rules

- Use functional components.
- Use TypeScript props when TypeScript is detected.
- Prefer composition via `children`.
- Use `forwardRef` for reusable interactive primitives when needed.
- Keep controlled and uncontrolled modes explicit.
- Expose `className` only when project conventions allow it.
- Avoid boolean explosion.

## Preferred API

```tsx
<Button variant="primary" size="md">Save</Button>
```

## Review Checks

- prop typing
- ref behavior
- composition
- hooks correctness
- accessibility
- token usage
