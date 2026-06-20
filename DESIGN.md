---
version: alpha
name: DaviMGDev Portfolio
description: A dark, modern design system for a developer portfolio — clean, technical, and precise.
colors:
  primary: "#60A5FA"
  primary-hover: "#93C5FD"
  primary-active: "#3B82F6"
  secondary: "#A78BFA"
  tertiary: "#34D399"
  neutral-950: "#0A0A0B"
  neutral-900: "#111113"
  neutral-850: "#18181B"
  neutral-800: "#1E1E22"
  neutral-700: "#27272A"
  neutral-600: "#3F3F46"
  neutral-500: "#71717A"
  neutral-400: "#A1A1AA"
  neutral-300: "#D4D4D8"
  neutral-200: "#E4E4E7"
  neutral-100: "#F4F4F5"
  neutral-50: "#FAFAFA"
  surface: "#111113"
  surface-elevated: "#18181B"
  surface-overlay: "#1E1E22"
  on-surface: "#F4F4F5"
  on-surface-muted: "#A1A1AA"
  on-primary: "#0A0A0B"
  success: "#34D399"
  warning: "#FBBF24"
  error: "#F87171"
  border: "#27272A"
  border-subtle: "#1E1E22"
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.03em
  display-md:
    fontFamily: Inter
    fontSize: 44px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: 0
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0.02em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0.04em
  code-lg:
    fontFamily: JetBrains Mono
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0.02em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.02em
rounded:
  none: 0px
  sm: 4px
  md: 8px
  lg: 12px
  xl: 16px
  xxl: 24px
  full: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  xxxl: 64px
  xxxxl: 96px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
    typography: "{typography.label-lg}"
    padding: 12px 24px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
  button-primary-active:
    backgroundColor: "{colors.primary-active}"
  button-secondary:
    backgroundColor: "{colors.surface-elevated}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    typography: "{typography.label-lg}"
    padding: 12px 24px
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-surface-muted}"
    rounded: "{rounded.md}"
    typography: "{typography.label-lg}"
    padding: 12px 24px
  card:
    backgroundColor: "{colors.surface-elevated}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.lg}"
    padding: 24px
  input:
    backgroundColor: "{colors.surface-overlay}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    typography: "{typography.body-md}"
    padding: 12px 16px
  code-block:
    backgroundColor: "{colors.neutral-950}"
    textColor: "{colors.neutral-300}"
    rounded: "{rounded.md}"
    typography: "{typography.code-md}"
    padding: 16px
---

# DaviMGDev Portfolio

## Overview

A dark, modern design system built for a developer portfolio. The aesthetic draws
from code editors and terminal interfaces — precise, high-contrast, and focused
on readability. Every element feels intentional, like well-written code.

The palette is rooted in deep charcoals and zincs with electric blue as the
primary accent. Purple and emerald add depth for secondary interactions and
success states. Typography pairs a clean humanist sans-serif (Inter) with a
monospace font (JetBrains Mono) for code and technical content.

## Colors

The color system follows a strict hierarchy: dark backgrounds, light text, and
vibrant accents that pop against the darkness.

- **Primary (#60A5FA):** Electric blue — links, focus rings, primary actions.
  The signature color that ties the portfolio together.
- **Primary Hover (#93C5FD):** Lighter blue for hover feedback.
- **Primary Active (#3B82F6):** Deeper blue for pressed states.
- **Secondary (#A78BFA):** Soft violet for tags, badges, and secondary highlights.
- **Tertiary (#34D399):** Emerald green for success states and code highlights.
- **Neutral Scale (950–50):** Zinc-based greys from near-black to near-white.
  Provides the full depth range for backgrounds, text, and borders.
- **Surface (#111113):** The deepest background layer — page body.
- **Surface Elevated (#18181B):** Cards, modals, and raised elements.
- **Surface Overlay (#1E1E22):** Tooltips, dropdowns, and floating UI.
- **On-Surface (#F4F4F5):** Primary text — high contrast against dark backgrounds.
- **On-Surface Muted (#A1A1AA):** Secondary text, captions, placeholders.
- **On-Primary (#0A0A0B):** Dark text on primary-colored backgrounds.
- **Border (#27272A):** Standard dividers and card outlines.
- **Border Subtle (#1E1E22):** Barely-visible structural dividers.

## Typography

Two type families create a clear hierarchy:

- **Inter** — The workhorse. Used for all body text, headlines, and UI labels.
  Its tall x-height and open apertures ensure excellent readability at small
  sizes, even on low-DPI screens.

- **JetBrains Mono** — The specialist. Used exclusively for code snippets,
  terminal output, inline code, and technical metadata. Its distinctive
  character shapes make code instantly recognizable as code.

The type scale uses a modular ratio with tight letter-spacing on headlines for
a compact, technical feel. Body text uses comfortable line heights (1.6–1.7)
for extended reading.

## Layout

A fluid container-based layout with a 1200px max-width for desktop content.
On mobile, everything collapses to a single column with generous padding.

Spacing follows an 8px base grid with a 4px half-step for micro-adjustments.
Cards use 24px internal padding. Sections are separated by 64–96px of vertical
space to give content room to breathe.

## Elevation & Depth

Depth is achieved through **tonal layering** rather than heavy box shadows.
Each elevation level uses a slightly lighter background:

- Level 0: Page background (`#111113`)
- Level 1: Cards and panels (`#18181B`)
- Level 2: Floating elements (`#1E1E22`)

Subtle 1px borders in `#27272A` define containment without visual weight.
Hover states use slight brightness shifts rather than shadows.

## Shapes

A **soft-square** shape language with 8px corner radius on all interactive
elements. Cards and containers use 12px. Badges and pills use full rounding.

This creates a cohesive look that's modern without being bubbly — the corners
are noticeable but not dominant.

## Components

- **Buttons:** Primary (filled blue), Secondary (elevated surface), Ghost
  (transparent). All use label-lg typography with 12px/24px padding.
- **Cards:** Elevated surface background, 24px padding, 12px radius. Used for
  projects, skills, and content blocks.
- **Inputs:** Overlay background with subtle borders. Clear label typography
  and generous padding for comfortable interaction.
- **Code Blocks:** Near-black background with JetBrains Mono. Used for syntax
  highlighting and terminal output display.

## Do's and Don'ts

- Do use the primary blue only for interactive elements (links, buttons, focus rings)
- Don't use blue for static text — it implies interactivity
- Do maintain the 8px spacing grid for consistent rhythm
- Don't stack elevation layers — one level of depth per element
- Do use JetBrains Mono for all code and technical content
- Don't use monospace for body text or headlines
- Do keep backgrounds dark and text light for maximum contrast
- Don't use pure black (#000) or pure white (#FFF) — use the zinc scale
- Do use emerald green for success/confirmation states only
- Don't mix success green with error red in the same visual context
