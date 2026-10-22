# Coin icons

Coin logos for Cypolio, served from this repo by jsDelivr:

```
https://cdn.jsdelivr.net/gh/eric-ho-github/coin-icons@master/icons/<symbol>.png
```

- One file per coin symbol, named by the lowercased symbol (`btc.png`, `ena.png`).
  Symbols that share a name share one file.
- 64×64 PNG. A logo that isn't square is scaled to fit within 64px.
- `no-icon-found.png` is what the app falls back to when a symbol has no file.

To add or replace an icon, commit the PNG under `icons/` with the symbol as its
name. jsDelivr picks up `master` within minutes; to force it for one file, open
`https://purge.jsdelivr.net/gh/eric-ho-github/coin-icons@master/icons/<symbol>.png`.
