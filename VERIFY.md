# VERIFY

Checkpoints for the GitHub profile README. Derived from `.design-system.md` §9.

## Checkpoints

| # | Area | Scenario | Status |
|---|------|----------|--------|
| 1 | HTML | All HTML tags are properly opened and closed | ✅ |
| 2 | Links | All `<a href>` URLs resolve (2xx/3xx; LinkedIn's 999 counts as resolve) | ✅ |
| 3 | Email | mailto address matches contact block | ✅ |
| 4 | Content | No empty `<a>` tags (href non-empty, link text non-blank) | ✅ |
| 5 | Length | README within 20–50 lines (business-card scope) | ✅ |
| 6 | Viewport | Full README fits in ≤ ~700px rendered height — masthead ≤ 56px, no `<br><br>`, no hairline rules | ✅ |
| 7 | Assets | Every SVG referenced in `<img src>` / `<picture>` exists at `assets/*.svg` and is valid XML | ✅ |
| 8 | Dark mode | Every `<picture>` has both a default `light` and `prefers-color-scheme: dark` source | ✅ |
| 9 | Monochrome | No accent color (`#B8301C` / `#D9533F`) appears anywhere in README or assets referenced by README | ✅ |
| 10 | No-inline-SVG | No raw `<svg>` / `<style>` / `<script>` tags in README | ✅ |
