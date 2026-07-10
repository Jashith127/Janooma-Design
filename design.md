# Janooma — Design System
### A modernized visual language for an AI-native business growth platform

> Note: this system was built from Janooma's current content, positioning, and copy tone (AI Workers, Industry Twins, "Discover → Execute → Grow"). It reimagines the visual layer to feel like a 2026 AI-product — closer to Linear, Vercel, or Attio than a typical SaaS marketing site.

---

## 1. Design Principles

- **Confident, not corporate.** Janooma sells autonomy and speed — the UI should feel engineered, not "designed by committee."
- **Dark-first.** AI-product feel over generic light SaaS. Light mode is a variant, not the default.
- **One accent, used sparingly.** A single high-energy color carries all emphasis — everything else is neutral.
- **Precision over decoration.** Thin borders, exact spacing, restrained gradients — no drop shadows or skeuomorphism.
- **Motion implies intelligence.** Subtle, purposeful animation (typing/streaming effects, node connections) reflects "AI worker doing the work" — never decorative bounce.

---

## 2. Color Palette

### Core (Dark — default theme)

| Token | Hex | Usage |
|---|---|---|
| `bg-base` | `#0A0A0F` | Primary background |
| `bg-surface` | `#121218` | Cards, panels |
| `bg-surface-raised` | `#1A1A22` | Modals, elevated elements |
| `border-subtle` | `#26262F` | Hairline borders/dividers |
| `border-strong` | `#38383F` | Input borders, active states |
| `text-primary` | `#F5F5F7` | Headlines, primary copy |
| `text-secondary` | `#A1A1AA` | Body copy, descriptions |
| `text-muted` | `#6B6B76` | Captions, metadata |

### Accent — "Signal Violet"

| Token | Hex | Usage |
|---|---|---|
| `accent` | `#7C5CFF` | Primary CTAs, links, active states |
| `accent-hover` | `#9078FF` | Hover state |
| `accent-muted` | `#7C5CFF1A` (10% opacity) | Accent backgrounds, chips, highlights |
| `accent-glow` | `#7C5CFF` at 40% blur | Gradient auras behind hero/key elements |

### Functional colors

| Token | Hex | Usage |
|---|---|---|
| `success` | `#3DD68C` | Verified, completed, "outcome" states |
| `warning` | `#F5B94D` | Pending, in-progress |
| `error` | `#FF5C5C` | Errors, destructive actions |
| `info` | `#5CC8FF` | Informational tags |

### Light mode (secondary theme)

| Token | Hex | Usage |
|---|---|---|
| `bg-base` | `#FAFAFC` | Primary background |
| `bg-surface` | `#FFFFFF` | Cards, panels |
| `border-subtle` | `#E5E5EA` | Dividers |
| `text-primary` | `#0A0A0F` | Headlines |
| `text-secondary` | `#5A5A66` | Body copy |
| `accent` | `#6A3FF5` | Slightly deepened for contrast on white |

**Rule of thumb:** accent color should touch no more than ~10% of any given screen — one CTA, one highlighted stat, one active nav state. Everything else stays neutral grayscale so the accent reads as *intentional*, not decorative.

---

## 3. Typography

### Typefaces

| Role | Font | Notes |
|---|---|---|
| Display / Headlines | **Geist** (or Inter Tight as fallback) | Tight tracking, geometric, confident |
| Body / UI | **Inter** | Workhorse — legible at small sizes, neutral |
| Data / Technical / AI output | **JetBrains Mono** or **Berkeley Mono** | Used for AI worker "prompts," code-like snippets, live outputs (e.g. "Find 50 distributors...") — reinforces the product's technical, agentic nature |

### Scale (desktop)

| Style | Size | Weight | Line-height | Letter-spacing |
|---|---|---|---|---|
| Display XL (hero H1) | 64–80px | 600 (Semibold) | 1.05 | -0.02em |
| H1 | 48px | 600 | 1.1 | -0.02em |
| H2 | 32px | 600 | 1.2 | -0.01em |
| H3 | 22px | 600 | 1.3 | -0.01em |
| Body Large | 18px | 400 | 1.6 | 0 |
| Body | 16px | 400 | 1.6 | 0 |
| Small / Caption | 13px | 500 | 1.4 | 0.01em |
| Mono / Data | 14px | 400–500 | 1.5 | 0 |

**Guidance:**
- Headlines: Semibold, never Bold or Black — keeps the tone assured rather than shouty.
- Use the mono font as a signature device: whenever the site quotes an example prompt or shows "AI worker output," switch to mono. This becomes a recognizable brand pattern (similar to how AI-native products show "thinking" states).
- Avoid italics almost entirely — reserve for rare emphasis only.

---

## 4. Iconography & Imagery

- **Icon style:** 1.5px stroke, rounded caps, minimal (Phosphor or Lucide icon sets fit well) — no filled/glyph icons except for status dots.
- **Imagery:** avoid stock photography entirely. Replace with:
  - Abstract node/graph visuals (representing "Industry Twins" / Business Opportunity Graph)
  - Data visualizations — live-feeling charts, ranked lists, verification badges
  - Soft gradient meshes (violet → deep blue → black) as ambient background texture, never full-bleed loud color
- **Avatars / worker identity:** each AI Worker (SDR, Researcher, Marketing) gets a simple abstract glyph/monogram in accent color, not a cartoon robot — keeps tone premium and serious.

---

## 5. Surfaces, Depth & Shape

- **Corner radius:** 12px for cards, 8px for buttons/inputs, 999px (full) for pills/tags. Consistent scale — no mixing of radii sizes on the same screen.
- **Borders over shadows.** Depth comes from 1px hairline borders (`border-subtle`) and subtle background-luminance shifts, not drop shadows. This is the core "modern AI dashboard" cue.
- **Glow, not shadow.** Where elevation is needed (hero elements, active cards), use a soft accent-color blur glow rather than a black drop shadow.
- **Glass panels used sparingly** — one subtle `backdrop-blur` moment (e.g. nav bar on scroll) rather than glassmorphism throughout.

---

## 6. Motion

- **Duration:** 150–250ms for UI feedback, 400–600ms for section reveals.
- **Easing:** `cubic-bezier(0.16, 1, 0.3, 1)` (ease-out-expo feel) — quick start, soft settle. Reads as "responsive," not bouncy.
- **Signature motion:** a typewriter/streaming-text effect for example prompts ("Find 50 distributors for my LED switchgear...") — ties directly to the product's core interaction model.
- **Avoid:** parallax gimmicks, bounce/elastic easing, spinning loaders — replace loaders with pulsing skeleton states or progress text ("Discovering... Enriching... Ranking...").

---

## 7. Voice-to-Visual Alignment

Janooma's copy is short, declarative, outcome-first ("Tell your AI worker what you want. It does the rest."). The visual system should match:

- Short line lengths, lots of negative space around headlines
- One idea per screen section — avoid dense, multi-column marketing walls
- Numbers and outcomes (50 distributors, 200 leads) rendered as **large mono-font stats**, not buried in paragraph copy
- Status/verification language ("Verified," "Ranked," "Enriched") shown as small pill badges in `success` or `accent-muted` — reinforces trust and machine-verified precision

---

## 8. Quick Reference — CSS Variables

```css
:root {
  /* Backgrounds */
  --bg-base: #0A0A0F;
  --bg-surface: #121218;
  --bg-surface-raised: #1A1A22;

  /* Borders */
  --border-subtle: #26262F;
  --border-strong: #38383F;

  /* Text */
  --text-primary: #F5F5F7;
  --text-secondary: #A1A1AA;
  --text-muted: #6B6B76;

  /* Accent */
  --accent: #7C5CFF;
  --accent-hover: #9078FF;
  --accent-muted: rgba(124, 92, 255, 0.1);

  /* Functional */
  --success: #3DD68C;
  --warning: #F5B94D;
  --error: #FF5C5C;
  --info: #5CC8FF;

  /* Type */
  --font-display: 'Geist', 'Inter Tight', sans-serif;
  --font-body: 'Inter', sans-serif;
  --font-mono: 'JetBrains Mono', monospace;

  /* Radius */
  --radius-sm: 8px;
  --radius-md: 12px;
  --radius-full: 999px;

  /* Motion */
  --ease-out: cubic-bezier(0.16, 1, 0.3, 1);
}
```
