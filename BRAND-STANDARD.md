# HARCOM Industries — Shared Brand Standard

**Status:** Canonical design guidance for all HARCOM Industries projects.  
**Owner:** HARCOM Industries  
**Copyright:** © 2026 HARCOM Industries. All rights reserved.

## Brand rule

Use the supplied official HARCOM Industries logo: the black Viking-head silhouette, HARCOM orange beard and eyes, HARCOM INDUSTRIES wordmark, and Celtic-knot divider. Do not redraw, replace, recolour, crop away the wordmark for primary branding, or substitute a generic letter badge. Small app icons may use a carefully derived mark only when the full logo cannot fit; the full logo must remain available in the About/help/brand area.

## Shared palette

- Graphite / near-black foundations: `#0D1217`, `#171D23`
- Gunmetal panels: `#202A33`, `#263642`
- Steel borders and text: `#526572`, `#AAB9C2`
- Icy-blue interaction and information: `#9EDCF2`, `#BCECFF` (use `#BCECFF`)
- HARCOM orange: `#FF7518`; accent orange may use `#FF8C1A`
- Safe/ready status: muted green; warnings and destructive actions must remain visually distinct.

## Interaction and layout principles

- Use dark gunmetal surfaces, clear typography, generous touch targets, consistent spacing and readable contrast.
- Icy blue is for information, focus and ordinary actions; orange is for brand accents, selected emphasis and warnings.
- Prefer functional, restrained technical detailing over decorative clutter.
- Preserve keyboard/screen-reader labels, visible focus states, reduced-motion preferences and mobile responsiveness.
- Do not imply a product is offline, encrypted, backed up, verified or secure unless that state is true and clearly scoped.
- No product should depend on remote fonts or decorative remote assets for its core interface. Offline products must cache all local brand assets.

## Product expression

- **HARCOM Vault:** secure-storage terminal; official logo, precise status, recovery and security controls.
- **Rook’s Field Companion:** rugged field terminal; same logo and palette, optimised for outdoor reading and one-handed use.
- **Viking AI Council:** command-and-analysis interface; shared identity, with distinct voices and clear evidence/status reporting.
- **OFFGRID:** future offline companion; shared identity, reliability-first, with no implementation until its project is authorised.
- **HARCOM Industries website:** public corporate identity and product directory.

## Release and safety rules

- Implement changes on a development branch when a working baseline exists.
- Keep live releases intact until validation passes.
- For Android, CI success is not the same as a physical Samsung device test.
- For offline web apps, validate the complete app shell and service-worker cache before publishing.
- Do not modify a frozen baseline merely to apply branding; record the work and resume after its scheduled review.
- Do not claim deployment until the production workflow reports success and the published page has been checked.

## Rollout status — 3 November 2026

- Official website already displays the supplied HARCOM Industries logo.
- Field Companion official-logo change is being validated for deployment.
- Vault official-mark change is in an isolated pull request and awaiting Android CI/emulator checks.
- Viking AI Council remains frozen for its scheduled baseline review on 4 November.
- Paradox Vault source has not been verified; do not alter it until the actual source is recovered and inspected.
