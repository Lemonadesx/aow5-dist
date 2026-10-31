# aow5-dist

Build artifacts mirror. `aow5.json` is the release manifest consumed by the launcher.

- `latest` — currently published build (`null` when nothing is published)
- `min_launcher` — oldest launcher build still able to self-update
- `aow5/` — per-version binaries (only when kept in-tree; large builds live in Releases)
