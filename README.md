# my-portfolio

A single-page personal portfolio for Syeda Malika Zainab Kazmi, built with an AI-assisted Markdown → HTML workflow.

## Live sections

- Hero with name, tagline, and animated "snake trail" signature (a nod to my Snake Game project)
- About me
- Skills (icon cards with a staggered reveal animation)
- Projects — featuring my deployed Snake Game: https://snake-game-273952851429.asia-southeast1.run.app/ (with a pulsing "Play the game" button)
- Contact — email, GitHub, city
- Dark mode toggle (sun/moon icon in the nav, remembers your choice via localStorage)
- GitHub profile link: https://github.com/smalikazainab
- Custom animated cursor, intro preloader, magnetic buttons, and a scrolling marquee strip (desktop only — cursor/magnetic effects auto-disable on touch devices)

## Theme

Navy blue (`#0A1F44`, `#071730`), white, and light blue (`#4FA8E0`) — chosen for a clean, professional, tech-forward look. Fonts: Sora (headings), Inter (body), JetBrains Mono (labels/tags).

## Workflow / prompts used

**Step 1 — Content in Markdown:** wrote About/Skills/Projects/Contact as plain Markdown first.

**Step 2 — Initial HTML generation:**
> "Turn this into a clean, mobile-friendly, one-page portfolio website in HTML. Use a navy blue, white, and light blue colour theme, and make it look professional. Give me a single HTML file."

**Step 3 — Iteration prompts used:**

1. "Grade this page out of 10 for design and readability, then improve it — make it stand out from typical AI-generated portfolios instead of using a generic template look."
2. "The project section embeds the live game in an iframe — check if that could break or show an error if the host blocks embedding, and replace it with a safer approach that still feels interactive and professional."
3. "Add a distinctive visual signature tied to the person's own project (the Snake game) rather than a generic gradient/hero, and make sure the mobile nav, contact links, and animations all work without errors."
4. "The page looks a bit simple/boring — add subtle non-complex animations, a dark mode that respects the existing navy/white/light-blue theme, and GitHub/LinkedIn/email links, without adding visual clutter."
5. "Make it feel as interactive as a high-end animated agency portfolio (inspired by a Dribbble reference) — add a custom cursor, an intro reveal animation, magnetic buttons, and a scrolling marquee strip, while keeping the same navy/white/light-blue theme and single-file structure."

## Files

- `index.html` — the complete, self-contained website (no external files except Google Fonts CDN)
- `README.md` — this file

## To publish

Push this repo to GitHub, then enable GitHub Pages (**Settings → Pages → Deploy from branch → `main` → `/ (root)`**) to get a live link.
