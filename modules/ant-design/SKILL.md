# Ant Design Module

## Purpose

Apply Ant Design / Ant Design Vue integration rules.

## Rules

- Prefer library components before custom primitives.
- Customize via theme tokens where possible.
- Avoid deep CSS overrides.
- Avoid wrapping library components without meaningful behavior.
- Preserve built-in accessibility and keyboard behavior.

## Customization Order

1. Ant Design theme tokens
2. FAOS semantic tokens
3. Component props
4. CSS override only when necessary
