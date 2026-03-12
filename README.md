# BTC GitHub Pages

This directory is a pure static GitHub Pages build.

Files:
- `index.html`: browser-only BTC price page
- `.nojekyll`: disables Jekyll processing on GitHub Pages

Price source order:
1. OKX
2. Binance

Deploy:
1. Create a GitHub repository.
2. Put `index.html` and `.nojekyll` in the repository root.
3. Enable GitHub Pages from the default branch root.

Notes:
- No ECS, Nginx, Python, systemd, or server API is required.
- Browser fetch requires outbound network access; Surge/proxy can handle overseas API access.
