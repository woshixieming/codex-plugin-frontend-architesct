# Module Router

## Purpose

Select active FAOS modules based on project context and user intent.

## Module Types

- framework module
- styling module
- UI library module
- domain module
- platform module

## Routing Table

| Context | Module |
| --- | --- |
| React / Next.js | modules/react |
| Vue 2 | modules/vue2 |
| Vue 3 / Nuxt 3 | modules/vue3 |
| Tailwind / UnoCSS | modules/tailwind |
| Ant Design / Ant Design Vue | modules/ant-design |
| Element Plus / Element UI | modules/element-plus |
| Admin / CRM / ERP / Dashboard | modules/dashboard |
| Mobile / H5 | modules/mobile-h5 |

## Output Format

```text
MODULE ROUTING

Framework Module:
Styling Module:
UI Library Module:
Domain Module:
Reason:
Conflict Resolution:
```

## Conflict Resolution

When rules conflict:

1. explicit user instruction
2. existing project convention
3. UI library module
4. framework module
5. styling module
6. domain module
7. core rule
