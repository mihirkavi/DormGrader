# README images

Images used by the root [README](../../README.md) of DormGrader. They are presentation assets only; the app does not load them.

## Files

| File | What it is |
| --- | --- |
| `banner-light.png`, `banner-dark.png` | Title banner for light and dark GitHub themes, rendered from [`source/banner.html`](source/banner.html) with headless Chromium |
| `hero.jpg` | Framed desktop and phone screenshot used at the top of the README |
| `screenshots/features.jpg`, `top-dorms.jpg`, `how-it-works.jpg` | Sections of the website prototype. Statistics and dorm cards on the page are placeholder content |

## Visual identity

DormGrader's README borrows the language of a **report card**: student review sites grade housing the way a school grades a student, so the banner shows a tilted sample report card with letter grades for the five rating categories and an "A overall" stamp.

- **Fonts:** Playfair Display (black and italic) for headlines and grades, Outfit for everything else, the same pair the website prototype uses.
- **Colors:** gold `#f4c430` and amber `#ff9f1c` (the site's gold gradient), night `#0a0a0f` / card `#12121a` for the dark banner, warm paper `#fbf6e9` with ink `#12121a` for the light one. Gold text on paper uses the darker `#9a6a00` for contrast.
- **Badges** use `f4c430`, `ff9f1c`, `12121a` and `a0a0b0`. The friendly emoji section headers stay, matching the consumer tone.
- The grades are labelled "Sample" and "Illustration · not real ratings": DormGrader has no reviews.
- **Re-render:** see [`source/README.md`](source/README.md).

## How they were made

Captured on 2026-10-26 from the live prototype (https://mihirkavi.github.io/DormGrader/) with headless Chromium at 1440 × 900 (desktop) and 390 × 844 (phone). Screenshots are framed in a browser window or phone outline by a small Playwright script, then saved as JPEG.

## Notes for agents

- Screenshots must show only public pages or demo data, never personal, financial or health information.
- Keep names lowercase with hyphens. When you replace an image, keep its file name so README links keep working, and update this table.
- Retake screenshots after visible interface changes so the README stays truthful.
