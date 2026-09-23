# rburns02.github.io

The developer website, served at the root of `rburns02.github.io`.

It exists for `app-ads.txt`. Ad buyers and AdMob only ever read that file at the
root of the domain on the App Store listing, so nothing nested inside another
repository can serve it — hence a user site rather than a folder in
`skipstone-support-`.

- `app-ads.txt` — authorised sellers. The publisher id must match AdMob exactly.
- `.nojekyll` — serve files byte for byte; no build step to reinterpret them.
- `index.html` — for people who trim the URL.
