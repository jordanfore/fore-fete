# FORE fête

The curated map of Paris Fête de la Musique 2026. 90 parties, one map, no gatekeeping.

Built for emerging creatives, independent thinkers and the community. We don't wait fore change, we make it.

## What's inside

- **90 events** across the weekend (Fri 19, Sat 20, Sun 21 June) — club nights, day parties, street parties, boat parties
- **Direct ticket / RSVP links** for every event that has one — straight to Shotgun, Dice, Partiful, Eventbrite, Fatsoma or the promoter's RSVP post. No bouncing through a middle page first
- **Real venue coordinates** — 75 of 90 events are pinned to the exact venue, the rest to the right area, with anything undisclosed clearly flagged "Location TBC"
- **20 street-food & indie food spots** and **51 street-language phrases**

## How it's better than before

- The map and the list are properly linked. Tap an event, the map flies to that exact pin and opens it. Tap a pin, the list jumps to that event.
- Every pin sits on the real venue, not a generic district centre, so events no longer stack on top of each other.
- Filter by type, day and status (Free / Tickets / Sold Out / Coming Soon), plus live search across names, venues and sounds.
- Direct ticket links surface as a clear button on every card and in every map popup.
- Fully self-contained: all data is embedded in `index.html`, so the site can't fail to load its data.

## Files

- `index.html` — the whole site, self-contained (HTML, CSS, JS and data all in one file)
- `data.json` — the same event / restaurant / language data as a clean JSON file, if you want to reuse it elsewhere
- `FETEMAPPER_Events_2026_CLEANED.xlsx` — the cleaned, enriched source spreadsheet (direct links, coordinates, normalised fields)
- `README.md` — this file

## How to update your live site (simple version)

Your existing site is at `https://jordanfore.github.io/fore-fete/`.

1. Download `index.html` from this folder.
2. Go to your repo: `https://github.com/jordanfore/fore-fete`
3. Click the old `index.html`, then the pencil (✏️) icon to edit.
4. Select all the old code and delete it, then paste in the new `index.html`.
5. Scroll down, write a short message like "Rebuild: direct links + accurate map", and click **Commit changes**.
6. Wait ~30 seconds and refresh your site. Done.

Prefer the terminal? Drop the new `index.html` into your local `fore-fete` folder and run:

```bash
git add index.html
git commit -m "Rebuild: direct ticket links + accurate venue map"
git push
```

## Tech

Vanilla HTML / CSS / JavaScript · Leaflet.js for the map · CARTO dark tiles · hosted free on GitHub Pages.

---

**FORE fête** — for the people, by the people. One FORE all.
