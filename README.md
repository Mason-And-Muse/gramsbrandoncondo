# gramsbrandoncondo.store

Static website served via **GitHub Pages** on the custom domain
[gramsbrandoncondo.store](https://gramsbrandoncondo.store).

## How it's wired

- **Hosting:** GitHub Pages, deploying from the `main` branch (root).
- **Custom domain:** set via the `CNAME` file → `gramsbrandoncondo.store`.
- **`.nojekyll`:** disables Jekyll processing (this is plain static HTML).

## DNS (at Hover)

Apex domain points at GitHub Pages' anycast IPs:

| Type | Host | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | mason-and-muse.github.io |

## Local preview

Just open `index.html` in a browser, or:

```sh
python3 -m http.server
```
