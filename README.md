# thehardestlessons.com

Static one-page site: 27 typical mistakes hardware founders make, from prototype to factory. Content is drawn from *The Hardest Hardware Lessons* and *The Hardest Factory Lessons* by Hans Stam (Google Drive); nothing is invented.

- `index.html` is the whole site (inline CSS, no build). Style matches thehardesthardwarelessons.com (`#0f0f0f`, accent `#e8c547`, Georgia).
- Factory-book mistakes (21 to 27) come from the intro and Chapters 1 to 5 only. Chapters 6 to 17 were not read; add them when wanted.

## Hosting (set up 2026-11-02)
- Repo `hansstam86/thehardestlessons`, GitHub Pages from `main` (root), custom domain via `CNAME`.
- GoDaddy DNS: 4 A records on `@` (185.199.108.153, .109.153, .110.153, .111.153) and `www` CNAME to `hansstam86.github.io`. The old 301 forward to thehardesthardwarelessons.com was removed.
- Enforce HTTPS: pending. GitHub has not issued the certificate yet; once it exists run
  `gh api -X PUT repos/hansstam86/thehardestlessons/pages -F https_enforced=true`.
