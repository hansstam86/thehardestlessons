# thehardestlessons.com

Static one-page site: 27 typical mistakes hardware founders make, from prototype to factory. Content is drawn from *The Hardest Hardware Lessons* and *The Hardest Factory Lessons* by Hans Stam (Google Drive); nothing is invented.

- `index.html` is the whole site (inline CSS, no build). Style matches thehardesthardwarelessons.com (`#0f0f0f`, accent `#e8c547`, Georgia).
- Factory-book mistakes (21 to 27) come from the intro and Chapters 1 to 5 only. Chapters 6 to 17 were not read; add them when wanted.

## Not done yet (each needs Hans's OK)
1. Create GitHub repo `hansstam86/thehardestlessons` and push.
2. Enable GitHub Pages (main branch, root) and Enforce HTTPS.
3. Add a `CNAME` file containing `thehardestlessons.com`.
4. At GoDaddy: remove the current forward on `thehardestlessons.com` (it forwards to thehardesthardwarelessons.com) and point DNS at GitHub Pages: 4 A records on `@` (185.199.108.153, .109.153, .110.153, .111.153) and `www` CNAME to `hansstam86.github.io`.
