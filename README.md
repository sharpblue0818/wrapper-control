# Wrapper Control

GitHub Pages control panel for iframe-compatible URL wrappers.

## Publish

1. Upload `index.html` and `wrapper-status.json` to the repository root.
2. In **Settings → Pages**, deploy from the `main` branch root.
3. Open `https://sharpblue0818.github.io/wrapper-control/`.

## Ban or unban a wrapper

1. Use the control panel to change the wrapper state.
2. Click **Download wrapper-status.json**.
3. Replace the repository's existing `wrapper-status.json` with the downloaded file and commit it.
4. Hosted wrappers check the status file every five seconds. GitHub Pages caching may add a short delay.

The ban affects only the wrapper. It does not alter or block the underlying destination website.
