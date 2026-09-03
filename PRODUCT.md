# Product

## Register

brand

## Users

Primary viewers are engineers, founders, and recruiters landing on the GitHub profile of Fan Affan (fancyism). They arrive from pinned repos, skill releases, or word of mouth, skim once on desktop or mobile, and decide in seconds whether this developer is credible, active, and worth following or hiring. Most view in light mode; dark mode must also work.

## Product Purpose

Present the profile masthead (assets/masthead.svg) and README as a single confident brand surface: who Fan is (a developer who turns repeated work into agents), what he ships (agent skills, MCP tooling, automation, shipped daily), and the personality (2am work, bugs-as-signature) without looking AI-generated. Success means the masthead reads as authored, memorable, and professional at 830px render width on both themes, with zero external font or script dependencies.

## Brand Personality

Playful-professional: precise engineering craft with warmth and wit. Confident, not loud. The fun lives in copy and one authored motion, never in decoration volume.

## Anti-references

- AI-slop gradient banners, glassmorphism, emoji-icon headers, typing-SVG templates
- Pixel-art mascot at banner scale (tried in v3/v4: reads amateur next to refined type; register clash)
- Terminal-native dark mode (green-on-black, scanlines): saturated second-order reflex for dev portfolios
- Editorial-magazine lane (display serif + italic + drop caps): wrong register for this profile

## Design Principles

1. One committed idea per banner; decoration volume zero.
2. System font stack only (SVG in img context cannot load webfonts); craft comes from composition, scale contrast, and drawn vector elements.
3. Self-themes via prefers-color-scheme; every animation honors prefers-reduced-motion; passes hp-svg-motion validator and premium audit (95+).
4. Banner text ends before x=620 guard in any two-column layout; measured with getBBox, not eyeballed.
5. Identity tokens: ink #20272F / paper #FCFDFE / dark-bg #161B22 / accent signal red #D61723.
