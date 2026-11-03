# Sadhoo homepage, option 2 ("Scatter")

An alternative homepage concept for the Sadhoo website revamp (thesadhoo.com). The base is minimal: a strict grid, small labels and lots of paper. A few moments break it on purpose: bottles you can drag around, pen scribbles, a taped photo collage and a jumbled cloud of notes. It's a single static page with no build step and no dependencies.

Live preview: https://claude.ai/artifact/DcYabwoKfLMwBZRdjXs7yA

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## What's in it

- `index.html`: the whole page (HTML, CSS and JS in one file)
- `img/`: product bottles (transparent cut-outs), 8 ml testers, pouch, lifestyle photos and the SVG logos

## Sections

1. Hero: four bottles scattered over the SADHOO logo. The letters rise on load, break apart on scroll and can be dragged.
2. Brand line: words light up and pen marks draw in as the line reaches the middle of the screen.
3. Note ticker: speeds up and leans with scroll speed, and reverses when you scroll back up.
4. The four: a plain index list. On desktop the bottle follows the cursor.
5. Our story: a taped, tilted photo collage.
6. Follow a note: a jumbled word cloud that drifts and moves away from the cursor.
7. Reviews: pinned paper notes.
8. Which one?: bottle, tester and pouch.
9. FAQ, newsletter and footer, where the logo letters fly in and settle.

Every animation turns off when the device's "reduce motion" setting is on.

## Before launch

- Swap the ratings and testimonials for verified reviews.
- Rebuild as a Shopify Online Store 2.0 theme (sections and blocks). This page is a design reference, not the theme itself.
