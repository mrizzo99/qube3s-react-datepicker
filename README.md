# React Datepicker Starter

A starter scaffold for building a reusable React datepicker component (headless logic + UI styled examples). This repo contains TypeScript-ready hooks, UI wrappers (Tailwind), a range picker, a popover-based DateInput (Floating UI), Storybook stories, and build configs for publishing.

## Quickstart

1. Install deps

```bash
npm install
# or
pnpm install
```

2. Run storybook (dev)

```bash
npm run storybook
```

3. Run example dev (Vite)

```bash
npm run dev
```

4. Build library

```bash
npm run build
```

## What’s included

- Headless hooks: `useCalendar`, `useRangeCalendar`
- UI components: `Calendar`, `RangeCalendar`, `DateInput`, `MobileCalendar`
- Storybook stories for quick iteration
- Vite / TypeScript build for publishing

## Next steps (recommended)

- Add ARIA attributes and full keyboard navigation per WAI-ARIA datepicker pattern
- Add unit + integration tests (Vitest + React Testing Library)
- Add more features: timezone handling, multi-month view, presets, time selection
- Create a headless-only export and a styled export for separate consumption
- Build a demo site and prepare marketing materials
