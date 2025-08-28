# Hudu Chatbot (n8n)


This repository hosts the GitHub Pages site and artifacts for the n8n-powered Hudu chatbot.


- **Docs site:** published via GitHub Pages (see `/index.md`).
- **Screenshots:** put them under `assets/img/` and update the image links as needed.
- **Workflows:** store your n8n JSON exports in `/workflows/` (optional).


## Quick Start
1. Add `index.md` and `_config.yml` (root or `/docs`).
2. Push and enable GitHub Pages in Settings → Pages.
3. Drop screenshots into `assets/img/`.


## What it does
- Treats every message as a Hudu KB/Important Info lookup.
- Prioritizes Cheat Sheet → POC; Important Info for services/vendors/etc.
- Uses Postgres Vector Store; falls back to Hudu API when RAG confidence is low.


## Contributing
Issues and PRs welcome.
