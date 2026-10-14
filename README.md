# WiSe Learning Library

A connected learning website for the WiSe Unity game, with feature guides, a workbook checklist, and linked source snapshots.

## Included

- 32 feature chapters and 19 workbook checklists.
- Search across all 85 Markdown pages and 226 C# source files.
- C# source viewer with exact-line links, syntax highlighting, and downloads.
- Bookmarks, reading progress, and checklist ticks saved in the browser.
- Light/dark modes and responsive navigation.
- A ZIP download of the original Markdown learning folder.

## GitHub Pages

This repository contains the static website at its root. `.nojekyll` preserves the Markdown content files and publishes the files directly.

The intended Pages configuration is the `main` branch, `/` root. The Pages URL is available in repository Settings → Pages once deployment completes.

The website serves the supplied learning-guide snapshots. It does not automatically update when the Unity source changes. Rebuild the content in the original `LearningWebsite` folder and copy its `dist/` files here to update this version.

## Local preview

Serve this folder over HTTP, for example `python -m http.server 8765`, then open `http://localhost:8765`.

The game source is included for study. Known implementation gaps are retained in the guides rather than hidden by the website.
