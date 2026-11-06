# Repository instructions

- The app is a single HTML file: `index.html`.
- The user requires a visible app version for every future user-facing update, under **Mehr → Einstellungen**.
- For each user-facing release, increment the semantic version (patch by default) consistently in `meta[name="app-version"]`, the document title, and `#appVersion` (both visible text and `data-version`). Update `#appVersionDate` with the release date and refresh the short release description in `#appVersionCard`.
- Keep the version card as static HTML at the start of `#more`, outside collapsed sections, so it remains visible even if a later script fails.
- App versions describe the loaded code. Do not change the `RPGV33` save key, clear browser storage, or modify saved gameplay data to update or display a version.
