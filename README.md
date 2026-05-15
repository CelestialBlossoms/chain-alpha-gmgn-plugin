# Chain Alpha GMGN Plugin

Public Chrome extension package for showing Chain Alpha CA analysis on GMGN token pages.

## Install

1. Download `gmgn_ca_clusters.zip` from the latest GitHub Release.
2. Unzip the package.
3. Open Chrome and go to `chrome://extensions`.
4. Enable Developer mode.
5. Click `Load unpacked` and select the unzipped extension folder.
6. Open a GMGN token page. The Chain Alpha panel appears on the page.

## Notes

- The extension runs on `gmgn.ai` pages.
- The extension calls the configured Chain Alpha API service for CA analysis and bottom abnormal token data.
- If the panel does not update after upgrading, reload the extension in `chrome://extensions` and refresh the GMGN page.

## Release File

- `gmgn_ca_clusters.zip`: packaged Chrome extension.
- `extension/`: unpacked extension source for direct loading or inspection.
