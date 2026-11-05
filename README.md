# oneclickpoland.com
Pierogi, poetry and pure Polish pride: OneClick Poland, the Polish sister site of OneClick Ireland and OneClick Italy.

- Built from the OneClick Italy template (shared header/footer in `js/layout.js`, region pages driven by `data/regions/<slug>.json`).
- Menu: standard OneClick menu plus **Gaming** and **Paczka**; Sport is **Kibic**.
- English | Polish switch: Polish text is in `js/i18n-pl.js` (page text) and under `"pl"` in each `data/regions/*.json`. **The Polish is a draft and must be checked by a Polish speaker before launch.**
- News feeds: `data/news/<slug>.json` (empty until the Make scenarios are connected). Story titles/summaries can carry `title_pl` / `summary_pl`.
- Map outlines: ppatrzyk/polska-geojson.
- Not yet set: Google Analytics tag, itinerary form webhook (`js/itinerary-form.js`).
