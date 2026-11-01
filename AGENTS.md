# AGENTS.md

## Architecture
A static, single-file site: `index.html` contains all markup, styles (`<style>`), and the countdown and redirect logic (`<script>`). There is no framework, no package.json, and no build step. `netlify.toml` publishes the repo root.

## Conventions and notes
- Keep it dependency-free and in one file unless the owner asks for more.
- The Telegram invite URL is duplicated in the CTA `href` and the `targetUrl` constant. Keep them in sync.
- The countdown is 15 seconds (`totalTime`). The SVG ring uses r=45, so its circumference is about 283.
- The `.timer-label` class styles only the "SEC" label. The countdown number keeps the larger `.timer-text` font.
