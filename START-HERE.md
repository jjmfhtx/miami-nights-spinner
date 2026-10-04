# Miami Nights Spinner

## Purpose
A prize wheel web page for the Miami Nights Homecoming dance. Hosted on GitHub Pages.

## Outcome
A single-page spinner that appears to give ~1-in-10 odds of winning but actually awards a win with 1-in-175 probability.

## Key details
- **Visual odds**: 10 segments, 1 pink "WIN" slice
- **Actual odds**: `Math.random() < 1/175`
- **Spin duration**: ~1 second
- **Theme**: Miami Nights branding (hot pink, teal, deep green) with dark/light mode toggle
- **Logo**: Transparent PNG extracted from the original white-background .webp
- **Hosting**: GitHub Pages via the `miami-nights-spinner` repo

## Files
- `index.html` — the complete spinner page (self-contained, no build step)
- `logo.png` — transparent Miami Nights logo header

## Constraints
- No build tooling; pure HTML/CSS/JS for GitHub Pages static hosting
- No external dependencies beyond Google Fonts (Righteous, Outfit)
