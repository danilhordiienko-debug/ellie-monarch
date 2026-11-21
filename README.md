# Ellie Monarch

Static profile website for Ellie Monarch, 55, a former flight attendant.

## Preview locally

With Python 3 installed, run from the repository directory:

```sh
py -3 -m http.server 8766 --bind 127.0.0.1
```

Open http://127.0.0.1:8766. No dependencies or build step are required.

## GitHub Pages

Publish the `main` branch from `/ (root)` in Settings > Pages.
Custom domain: `elliemonarch.my` (configured in `CNAME`).
DNS at Porkbun points the apex ALIAS and the `www` CNAME to
`danilhordiienko-debug.github.io`. HTTPS is served by GitHub Pages.

## Content

- `index.html`: page, styling, and Instagram browser instructions.
- `assets/hero.jpg`: banner photograph.
- `assets/card.jpg`: exclusive contact card photograph.
- Contact: https://t.me/elliemonarch
- Channel: https://t.me/+CI2m_1v7EFYxOWUy
- X: https://x.com/ellie_mona_?s=21
- Threads: https://www.threads.com/@ellie_monar?igshid=NTc4MTIwNjQ2YQ==
- Instagram: https://www.instagram.com/ellie_monar?hvrq=bGI4eDJqNXFldXRq

The page includes canonical and social preview metadata, Schema.org profile
data, and accessible social links. `robots.txt` references `sitemap.xml`.
Brand icon paths are embedded from Simple Icons commit
`32e030086fdc605196391aab28519b14dc4295b4` (https://github.com/simple-icons/simple-icons).

The browser instructions can be previewed with `?popup=1`.
