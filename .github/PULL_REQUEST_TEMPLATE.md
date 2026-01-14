Title: Revamp UI — always-visible terms cards and robust loader

This PR revamps the `index.html` UI so all license terms are visible by default and cards stack cleanly without overlap. It also adds a robust JSON loader that tries a local `terms.json` first and falls back to the GitHub raw file if needed. Search, print, and Save-PDF remain supported.

Files changed:
- `index.html` (revamped UI, search, print, PDF, debug overlay)
- `terms.json` (content copied from upstream)

Tested locally by running a static server in `Collab/`.