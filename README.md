# mushafuk-translations

Staged copy of **Quran meaning translations** and **translated tafsirs** (`tafsir/tercume`) from [mushafuk-online](https://github.com/nihomaho9-ui/mushafuk-online).

| | |
|--|--|
| Source commit | `4ff10584719e3df530136b3c0e81f141910d1557` |
| Intended public origin | `https://t.mushafuk.online` |
| Migration status | **STAGED COPY** — originals remain on main; **no cutover**; **Pages not enabled** |
| Total | **265868** files / **1332.9 MiB** logical |
| Quran translations | ~87.2 MiB (25 works) |
| `tafsir/tercume` | **1245.6 MiB** (ibnkathir / mukhtasar / saadi / muyassar) |
| Fits GitHub Pages ~1GB? | **No** (~1332.9 MiB combined) |

## Validation
- All `249493` `tafsir/tercume` files byte-identical to source (git blob SHA1).
- Quran translation sample intact vs previous `origin/main`.
- Canonicals still point at `https://mushafuk.online/...`.

## Notes
- See `URL_MAPPING.md`, `CNAME.intended`, `INVENTORY.json`.
- GitHub Pages has no native HTTP 301; do not treat meta-refresh as 301.
- CSS/JS extract skipped for tercume (~2.4% chrome only; would not reach 900 MiB).
