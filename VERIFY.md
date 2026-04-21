# VERIFY

Checkpoints for the GitHub profile README. All links, SVG assets, and design-system conformance must pass before pushing. Rules derived from `.design-system.md` §8.

## Checkpoints

| # | Area | Scenario | Status |
|---|------|----------|--------|
| 1 | HTML | All HTML tags are properly opened and closed | ✅ |
| 2 | Links | All `<a href>` URLs resolve (2xx/3xx) | ✅ |
| 3 | Email | mailto address matches contact block | ✅ |
| 4 | Content | No empty `<a>` tags (href non-empty, link text non-blank) | ✅ |
| 5 | Length | Profile README within 40–100 lines (business-card scope, not project-docs scope) | ✅ |
| 6 | Assets | Every SVG referenced in `<img src>` / `<picture>` exists at `assets/*.svg` and is valid XML | ✅ |
| 7 | Dark mode | Every `<picture>` has both a `light` and `prefers-color-scheme: dark` source | ✅ |
| 8 | Sections | Section numerals `§ 01`, `§ 02`, `§ 03` appear in order, no gaps, no skips | ✅ |
| 9 | Accent | `#B8301C` / `#D9533F` appears exactly once per SVG asset (masthead endcap only) | ✅ |
| 10 | No-inline-SVG | No raw `<svg>` / `<style>` / `<script>` tags in README (would be sanitizer-stripped) | ✅ |
