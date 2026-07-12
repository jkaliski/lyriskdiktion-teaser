# lyriskdiktion.se — teaser

A single-file, self-contained coming-soon page for **Lyrisk Diktion** — ett
självstudiematerial i sångdiktion för italienska, franska och tyska.

> Tidigare **lyriclab** — numera **lyriskdiktion.se** · Kommer hösten 2026

## Deploy

Everything lives in [`index.html`](index.html) (HTML + CSS + JS + the embedded
portrait, no external requests). GitHub Pages serves it as-is.

- **Pages:** Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
- **Custom domain:** add `lyriskdiktion.se` under Settings → Pages once the DNS
  records (an `ALIAS`/`ANAME` or four `A` records to GitHub's IPs, plus a
  `CNAME` for `www`) point at GitHub. Pages will then create the `CNAME` file
  for you.

## Content

The copy, palette and the three-language IPA card are lifted from the live
LearnHouse landing so nothing is invented — it mirrors the real courses
(6 italienska · 4 franska · 7 tyska delkurser) and the diction-coach feature.
