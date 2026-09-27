# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

static HTML/CSS (vanilla, no framework, no build step — user specified "pure CSS4"), deployed as GitHub Pages (`4fingers.github.io`)

## Users

Visitors who land on 4fingers' GitHub Pages profile site — recruiters, potential freelance clients, and other developers checking him out (via GitHub profile, shared link, or search) — deciding whether to reach out for freelance work. [Inferred from sibling project `4fingers/` and the personal-portfolio framing of the request.]

## Product Purpose

A personal landing page introducing 4fingers as a freelance Software/System Builder. Success = a visitor understands what he does, senses the "system builder" positioning and the human/cat detail, and has an obvious way to contact him.

## Positioning

Not a generic "developer portfolio" — frames 4fingers specifically as a **System Builder**: someone who designs and builds systems (small sites to complex enterprise systems), not just writes code. The differentiator the user asked to foreground: he does this work to support his two cats — a human, disarming detail against the otherwise technical "system builder" identity.

## Operating Context

Sibling project `../4fingers` (`4fingers.dev`) is his primary business site — SvelteKit + TailwindCSS, deployed via Docker/VPS/GitLab CI, brand color `#AEFE00`. This `4fingers.github.io` project is a separate, standalone static page (no build tooling), meant to ship straight to GitHub Pages.

## Capabilities and Constraints

- Single `index.html` (plus its own CSS/assets) — no framework, no bundler, no build step.
- "CSS 4 thuần" per user request: modern vanilla CSS (nesting, `:has()`, `@property`, container queries, etc. where they help) instead of a framework like Tailwind.
- Must be deployable as-is to GitHub Pages.

## Brand Commitments

- Handle: **4fingers**. Existing tagline: "Software/System Builder" / "Freelance Developer from Vietnam".
- Contacts (from sibling project, reused here): Telegram (`https://t.me/x4fingers`), GitHub (`https://github.com/x4fingers`), Email (`mailto:contact@4fingers.dev`).
- User's explicit direction for this page: dark-mode premium; dominant colors are **black + terminal green**; emphasize being a **system builder**; emphasize working to **feed his two cats**.

## Evidence on Hand

Bio content sourced from `../4fingers/src/routes/+page.svelte`:
- Freelancer since 2019, worked for clients around the world.
- Built small-to-medium websites, mobile apps, scripts for individual clients.
- Also researched, managed teams, and led projects building complex systems for enterprises.
- Self-described as professional, trustworthy, and working anonymously/discreetly.
- Does all of this "only for paying the bills and feeding my two cute cats."

No testimonials, case studies, or client names on hand — do not fabricate any.

## Product Principles

1. Lead with the system-builder identity, not a generic "full-stack dev" framing.
2. Keep the cats as a genuine, warm punchline — not a gimmick that undercuts credibility.
3. Dark, technical, terminal-flavored visual language should reinforce "systems," not just decorate.
4. Ship as a dependency-free static page — the constraint is the point (GitHub Pages, zero build).

## Accessibility & Inclusion

No product-specific requirement stated. Standard dark-mode contrast (WCAG AA for text) applies given the premium dark aesthetic.
