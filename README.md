# PLV
A single-page browser app that views and converts Apple Music / iTunes playlist exports into CSV or Excel (XLSX) files. Everything runs locally in your browser — no files are uploaded anywhere.

## Supported files

- Unicode Text (`.txt`)
- XML (`.xml`) — including library exports with multiple playlists
- M3U / M3U8 (`.m3u`, `.m3u8`)

## How to use

1. Open the HTML file in any modern browser.
2. Drag and drop one or more playlist exports onto the page.
3. Pick a playlist from the dropdown and choose which columns to include.
4. Export as **CSV** or **XLSX**, or copy the table to the clipboard.

## Features

- Open several files at once and switch between them
- Close a single playlist or a whole file
- Full-width layout toggle (remembered between visits)
- Optional "confirm before closing window" warning

## Dependencies

Requires an internet connection to load:

- SheetJS (from cdnjs) — for XLSX export
- Google Fonts — for typography
