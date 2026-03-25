# Aryan Rajvanshi — Portfolio (Upgraded)

**Production-grade single-file portfolio. "Signal in the Noise" aesthetic.**

## What's upgraded

### Design & Typography
- **New font stack**: DM Serif Display + IBM Plex Mono + Syne (vs generic system-ui)
- **Deeper dark theme**: `#07080f` charcoal base with layered radial glows
- **Teal + Amber accent duality**: data precision vs human insight
- **CRT scan-line texture** via CSS repeating gradient (subtle, tasteful)
- **Custom teal rule** replaces generic dividers

### Animations
- **Glitch text entrance** — hero name character-scrambles before resolving
- **Terminal typing effect** — eyebrow label types itself character by character
- **Number scramble** — stats cycle through random digits before landing on real values (hero terminal + project metrics)
- **Scan-line reveal** — thin teal horizontal sweep on cards/headers as they enter viewport
- **Teal → Amber cursor trail** — 6-point particle trail behind custom cursor
- **Cursor states**: hover (scale), text (rectangle), active (shrink), amber (colour shift)
- **GSAP ScrollTrigger** timeline spine, section reveals, project 3D tilt

### Sections
- **Hero terminal panel**: Bloomberg-terminal aesthetic with live-style stats
- **Projects**: scan-reveal effect, deeper project descriptions in Aryan's voice
- **Process tiles**: left-border accent on expand, colour-coded numbers
- **Timeline**: animated spine fill, improved prose, personal voice added
- **Skills**: diamond proficiency indicators + thin bar tracks (not ugly bars)
- **Observations**: teal pip hover animation
- **Contact**: full terminal/CLI aesthetic with prompt-style layout

### Technical
- 7/7 security headers in vercel.json (added CSP + HSTS)
- Footer year set via JS (no SSR concerns)
- Konami code easter egg with reading list
- Console easter egg for recruiters who open DevTools
- All external links: `rel="noopener noreferrer"`
- ARIA: skip link, aria-labels, aria-expanded, aria-controls, role="dialog"
- `prefers-reduced-motion` respected throughout
- Touch device detection (cursor + animations disabled on mobile)

## Deploy

### Vercel (recommended)
1. Push folder to GitHub
2. Import on vercel.com
3. Done — ~30 seconds

### Local preview
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Easter Eggs
- **Konami code** (↑↑↓↓←→←→BA): secret reading list modal
- **Console**: open DevTools → Console for personal message
- **Footer hint**: the code is right there if you look
