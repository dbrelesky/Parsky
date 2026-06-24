# Impeccable v3.5.0 — Command Summary

A frontend design skill that produces production-grade UI code. 25 commands grouped into 6 categories.

## Build — start or capture a project
- **`craft [feature]`** — shape, then build a feature end-to-end
- **`shape [feature]`** — plan UX/UI before writing code
- **`init`** — set up project context (PRODUCT.md, DESIGN.md, live config)
- **`document`** — generate DESIGN.md from existing code
- **`extract [target]`** — pull reusable tokens/components into a design system

## Evaluate — score what exists
- **`critique [target]`** — UX heuristic review with scoring
- **`audit [target]`** — technical checks (a11y, perf, responsive)

## Refine — improve existing work
- **`polish [target]`** — final quality pass before shipping
- **`bolder [target]`** — amplify bland/safe designs
- **`quieter [target]`** — tone down overstimulating designs
- **`distill [target]`** — strip to essence, remove complexity
- **`harden [target]`** — production-ready: errors, i18n, edge cases
- **`onboard [target]`** — first-run flows, empty states, activation

## Enhance — add a dimension
- **`animate [target]`** — purposeful motion
- **`colorize [target]`** — strategic color on monochromatic UIs
- **`typeset [target]`** — typography hierarchy and fonts
- **`layout [target]`** — spacing, rhythm, visual hierarchy
- **`delight [target]`** — personality, memorable touches
- **`overdrive [target]`** — push past conventional limits

## Fix — repair targeted issues
- **`clarify [target]`** — UX copy, labels, error messages
- **`adapt [target]`** — responsive across devices
- **`optimize [target]`** — diagnose & fix UI perf

## Iterate — live browser loop
- **`live`** — pick elements in the browser, generate visual variants

## Management
- **`pin <command>` / `unpin <command>`** — create/remove `/<command>` shortcuts across harness dirs

**Routing:** typed command → loads `reference/<command>.md` and follows it. No argument → context-aware recommendation from `context-signals.mjs` + the slop detector, then the full menu.
