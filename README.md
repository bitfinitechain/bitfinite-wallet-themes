# bitfinite-wallet-themes
Static theme server for the BitFinite wallet, served via GitHub Pages at **themes.bitfinitechain.org**.

- `themes` — JSON list consumed by the wallet's "Add more themes" screen
- `theme/<id>` — the theme archive (zip); its sha256 must match the `sha256` in `themes`
- `previews/<id>.png` — preview image shown on each theme card

Rebranded from the upstream themes to BitFinite logo art; each theme keeps its own colour palette.
