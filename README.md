# Emporio Armani Bahrain — product photo copies

Backup copies of every product photo used on the website (repository `Armani-BAH/armani-site`).

- The photos are in `img/`, one JPEG per photo link (max 1200 px wide).
- The website loads photos from Armani first. If a link stops working, it switches to the copy here automatically.
- The **Photo backup** job (Actions tab) runs every Friday morning, Bahrain time: it saves copies of new photos,
  checks that the original links still work, and posts a report under **Issues**.
- `REPORT.md` is the latest report. `index.json` lists which copy belongs to which original link.

Please don't rename or delete files in `img/` — the website finds each copy by its file name.
