# eidenwilson.github.io

Personal site of Eiden Wilson Neralaily: data science student in Munich. One static page, no build step, no tracking.

The design follows [Macro Risk Monitor](https://eidenwilson.github.io/macro-risk-monitor/): set like a bookkeeping sheet, with blue-black ink, one red accent, ruled sections instead of cards, and Sofia Sans Semi Condensed (SIL Open Font License, `assets/fonts/OFL.txt`) served from the site itself.

## Files

```
index.html              the page
404.html                shown by GitHub Pages for unknown addresses
assets/css/style.css    all styles (tokens at the top)
assets/fonts/           the typeface, Latin and Latin Extended
assets/img/             project picture (WebP) and the link preview (og.png, 1200x630)
favicon.svg, robots.txt, sitemap.xml
```

## Run locally

```bash
python -m http.server 8000      # then open http://localhost:8000
```

## Deploy (free)

1. Create a public repository named exactly `EidenWilson.github.io`.
2. Push these files to its `main` branch.
3. Settings, Pages: deploy from branch `main`, folder `/ (root)`. The site goes live at https://eidenwilson.github.io/ within a minute.

`robots.txt` at the root of that domain also points search engines at Macro Risk Monitor's sitemap.

## Update

Projects, experience and skills are plain HTML in `index.html`, one `<li>` per entry. Keep each description to what a reader can check: a number, a link, the stack.
