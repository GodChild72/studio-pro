# Studio Pro

This repository now includes a working Studio Pro landing/demo experience and a default homepage redirect to the interactive studio.

## Files
- `index.html` — default homepage redirect to the main Studio page
- `studio.html` — interactive browser-based music studio demo
- `Studio Pro.html` — alternate Studio page
- `README.md` — basic project notes

## Run locally
Open `index.html` in a browser, or use a local static server:

```bash
python -m http.server 8000
```
Then visit:
- http://localhost:8000/

## Notes
- The project is intentionally lightweight and static.
- The main interactive features use the browser Web Audio API.
- Payment placeholders in the pricing version are still ready to be replaced with real links.
