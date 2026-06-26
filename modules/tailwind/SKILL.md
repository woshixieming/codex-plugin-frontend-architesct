# Tailwind Module

## Purpose

Apply Tailwind / UnoCSS compatible design system rules.

## Rules

- Prefer theme tokens.
- Avoid arbitrary values unless already a project convention.
- Extract repeated class groups into reusable components or utilities.
- Use semantic variants through component props.
- Keep responsive classes consistent.

## Avoid

```tsx
<div className="bg-[#ff0000] p-[13px] rounded-[7px]" />
```

## Review Checks

- arbitrary values
- repeated class groups
- responsive class consistency
- dark mode consistency
- token mapping
