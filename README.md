# Leckerschmecker Next Gen Feed — Prototype

A prototype of what the **Taboola Next Gen Feed** would look like on a real publisher's site — applied to [Leckerschmecker.me](https://www.leckerschmecker.me) (German food/recipe publisher).

**Live preview:** https://danielleh-bot.github.io/leckerschmecker-nextgen-feed/

## What this is

- Faithful recreation of the Leckerschmecker publisher chrome (header, nav, article page, brand green)
- The redesigned Taboola feed applied **in-context**, below the article
- All content is food/recipe themed and in German to match the publisher's audience

## Feed patterns included

1. Hero card (2:1, trending)
2. Two portrait cards (organic + sponsored)
3. Video card with hover autoplay, progress bar, sound toggle
4. Horizontal carousel (seasonal recipes)
5. Full-bleed glass-morphism native ad
6. Mosaic layout (1 tall + 2 stacked)
7. Stream section (large + horizontal + 2-up pair)
8. Three-up portrait row
9. Second carousel (editor's picks)
10. Final stream with load-more

## Assets

- Keyword-locked [loremflickr](https://loremflickr.com) images — each card pulls a content-relevant photo based on its topic (e.g. `pasta,lemon,ricotta`, `sourdough,bread,artisan`)
- Pexels video for the noodle-making autoplay card
- Inline SVG icons (no icon font dependency)

## Adaptations from the generic mockup

- Dark green (`#2D5A27`) brand color replaces the neutral dark navy
- German copy throughout (Beliebt, Anzeige, Rezept, Neu, Exklusiv)
- Custom "Rezept" publisher badge
- Contextual sponsors: HelloFresh, Dr. Oetker, Philips, TUI, Flink — not generic tech/finance

## Status

Internal prototype — shareable for feedback from stakeholders and the advisory board.
