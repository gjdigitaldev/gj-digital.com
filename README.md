# gj-digital.com

Marketing site for **GJ Digital LLC** — an independent app development studio.

- Static HTML/CSS, hosted on **GitHub Pages**.
- Custom domain **gj-digital.com** (DNS managed in Squarespace).
- Single page: `index.html` + `styles.css`.
- `CNAME` pins the custom domain; `.nojekyll` disables Jekyll processing.

## DNS (Squarespace)

Apex `@` → four GitHub Pages A records:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

`www` → CNAME `gjdigitaldev.github.io`

## Edit / publish

Bump `styles.css?v=N` on every CSS change (cache-busting), commit, and push to
`main` — GitHub Pages redeploys automatically.

Contact: info@gj-digital.com
