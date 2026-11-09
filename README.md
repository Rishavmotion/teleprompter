# Cue Prompter

A free teleprompter that runs in the browser. Paste a script, press Start, read.

- Single static page: `public/index.html`
- Hosted on Cloudflare Workers (static assets). Deploy with `npm run deploy`.
- Script and settings are saved in the browser's localStorage. Nothing is uploaded.

Keys: Space play/pause · ↑↓ speed · + − text size · [ ] column width · M mirror · G reading line · F fullscreen · Home restart · ← back 5 s · Esc back to editor. Right arrow / Page Down toggle play, so presentation clickers work.
