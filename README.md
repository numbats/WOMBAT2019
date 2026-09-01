# WOMBAT2019

Static recreation of the WOMBAT2019 workshop website, sourced from the
Wayback Machine snapshot:
https://web.archive.org/web/20200806143343/https://www.monash.edu/business/wombat2019

The page content is unchanged from the archived snapshot. All assets
(images, PDFs, stylesheets, script) were downloaded from the archive and
are served locally from `assets/`, so the page works without any
dependency on monash.edu or web.archive.org still being reachable.

## Known gaps

Two images referenced by the original page were never captured by the
Wayback Machine crawler, so they can't be recovered from the archive:

- Galit Shmueli's headshot in the Invited Speakers table (still points at
  the original monash.edu URL as a best-effort fallback).
- The "Venue" tile's background image in the Register section (given a
  plain black fallback background so the white text stays legible).

## Addition beyond the archive

A "Slides" call-to-action was added alongside the existing "Program" one,
the two now sharing a single block as side-by-side tiles (stacking on
mobile), linking to the workshop's presentation slides:
https://drive.google.com/drive/folders/1Jk7rIG9u80ObDFnjWpus9Y13sB5z9isg

## Viewing locally

```
python3 -m http.server 8000
```

then open http://localhost:8000/index.html
