# Wonder Robotics investor briefing

Thirteen slides, one file. Served by GitHub Pages from `main`.

- `index.html` is the whole deck: markup, styles and the small script for the arrow keys.
- `assets/` holds the mark (exported from the site's own `src/mark.js`) and byte-identical copies
  of the site's images, the two founder portraits from the corporate profile, and the icons.

## Where the content comes from

Every line is from the Wonder Robotics site (`wonder-robotics-site`, commit `8253f19`) or the
corporate profile. Market figures carry their source on the slide and were each checked against
the page they came from on 27 September 2026.

## Figures still to come

A dashed box is a figure nobody has supplied yet. Never replace one with an estimate.

All on slide 13, The ask: raise, instrument, use of funds, raising entity, revenue to date,
signed work, open quotes, gross margin, serviceable market.

## Rules the deck keeps

- The building is shown from the capture. Every concept, visualisation and drawing carries the
  label the site gives it. Nothing not yet built is shown as built.
- Published prices only, AUD ex GST. No cost, buy price or margin.
- The page carries `noindex`.

## Editing

Sizes inside a slide are written in sheet pixels (1920 by 1080) times `--u`, so the sheet scales
to any screen with no script. Under 760 px wide the slides become a column of cards at reading size.
