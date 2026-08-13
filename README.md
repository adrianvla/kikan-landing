# kikan.net landing

Stealth "Please wait" gate for the kikan.net apex (GitHub Pages). A tiny script queries https://ip2c.org/s for the visitor's country and auto-redirects: RU goes to https://ru.mlearn.kikan.net (the GitHub Pages mirror for regions where Cloudflare is slow or blocked), everyone else to https://mlearn.kikan.net. The URL suffix (path, query, hash) is preserved. If the lookup fails or times out (5s), or JS is off, plain region links appear as a fallback.

kikan.net is reserved as a future homepage. `index.html` and `404.html` hold identical content so unknown paths behave the same. `CNAME` lists `kikan.net` and `www.kikan.net`.
