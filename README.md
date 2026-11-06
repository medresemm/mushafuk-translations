# mushafuk-translations

Staged copy of **Quran meaning translations** from [mushafuk-online](https://github.com/nihomaho9-ui/mushafuk-online).

| | |
|--|--|
| Source commit | `4ff10584719e3df530136b3c0e81f141910d1557` |
| Intended public origin | `https://t.mushafuk.online` |
| DNS (owner-added) | `t` CNAME → `nihomaho9-ui.github.io` |
| Migration status | **STAGED COPY** — originals remain on main site; **no cutover**; **GitHub Pages not enabled** in this push |
| Scope files / size | **16371** files / **87.2 MiB** (logical) |

## Included
- 25 Quran translation works (paths from `/translations/` catalog), e.g. `az/tercume`, `en/translation`, `tr/meal`, …
- Hub: `translations/`, `translations.html`
- Shared CSS/JS under `assets/shared/` (exact-duplicate extract; body text unchanged)
- Deps: `lib.js`, `site.css`, `site.js`, `audio.js`, `fonts.css`, `icon.png`, `sources.html`, filtered `lib-list.json` (k=tr)
- Font used by pages: `yazi-fonts/uthmanic-hafs.woff2`

## Excluded (on purpose)
- **`tafsir/tercume/`** (~1245 MiB) — translated *tafsir*, listed under tafsir not the translations hub; left on main
- Arabic tafsir, mushaf page chrome, Ulum, irab/gharib full trees

## SEO / cutover notes
- HTML `rel=canonical` still points to `https://mushafuk.online/...` until cutover (avoids competing index if mirror is previewed).
- See `URL_MAPPING.md` and `CNAME.intended`.
- GitHub Pages does **not** provide native HTTP 301; plan redirects at cutover carefully (do not use fake meta-refresh as 301).

## Validation
See companion agent reports under local `pages-seo-opt/results/` (not necessarily in this repo).
