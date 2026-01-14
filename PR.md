# Pull Request: Revamp UI — always-visible terms cards and robust loader

### Summary
- Rebuilt `index.html` UI so all terms are visible by default and cards stack without overlap
- Added a robust JSON loader (local `terms.json` -> fallback to GitHub raw)
- Kept search, print, and PDF export working
- Added an optional `?debug=1` overlay to help diagnose page rendering

### How to test
- Run a local static server in `Collab/` and open the page
- Try with and without `terms.json` present to confirm fallback

### Notes
Tested locally; branch lives at `EntropyRedux/LTA.github.io:feature/revamp-terms`.