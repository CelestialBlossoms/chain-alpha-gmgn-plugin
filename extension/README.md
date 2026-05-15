# Chain Alpha GMGN CA Clusters

Manifest V3 Chrome extension for showing Chain Alpha CA analysis on GMGN token pages.

## Usage

1. Open `chrome://extensions`.
2. Enable Developer mode.
3. Click `Load unpacked`.
4. Select this `extension` folder.
5. Open a GMGN token page.

The extension calls the configured Chain Alpha API service from the background service worker.

## Troubleshooting

- After changing extension files, reload the extension from `chrome://extensions`.
- If the panel does not appear, confirm the current page is a GMGN token page and refresh the tab.
- If API data is unavailable, confirm the Chain Alpha API service is reachable.
