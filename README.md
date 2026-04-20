# Stratus Aviation — stratusaviation.org

Production website for **Stratus Aviation**, hosted on GitHub Pages.

## Repository Structure

| File | Purpose |
|---|---|
| `index.html` | Main site — all CSS, JS, and logo assets self-contained |
| `404.html` | Custom error page with auto-redirect to `/` |
| `CNAME` | GitHub Pages custom domain configuration |
| `robots.txt` | Search engine crawl directives |
| `sitemap.xml` | URL map for Google Search Console |
| `share-image.png` | OG/social preview image (3000×2000) |
| `n6979n_01.jpg` → `n6979n_07.jpg` | Aircraft photos — 1979 Cessna T210N (N6979N) |
| `n735uf_01.jpg` → `n735uf_09.jpg` | Aircraft photos — 1977 Cessna 182Q (N735UF) |

## Deployment

This site deploys automatically via **GitHub Pages** on every push to `main`.

Settings → Pages → Source: **Deploy from branch** → Branch: `main` / `root`

Custom domain: `stratusaviation.org`  
Enforce HTTPS: ✅

## Aircraft Images

Upload photos named exactly as follows — GitHub Pages is **case-sensitive**:

**N6979N — 1979 Cessna T210N Turbo Centurion II** (`$260,000`)
```
n6979n_01.jpg  ← hero (shown on card)
n6979n_02.jpg
n6979n_03.jpg
n6979n_04.jpg
n6979n_05.jpg
n6979n_06.jpg
n6979n_07.jpg
```

**N735UF — 1977 Cessna 182Q Skylane** (`$165,000`)
```
n735uf_01.jpg  ← hero (shown on card)
n735uf_02.jpg
n735uf_03.jpg
n735uf_04.jpg
n735uf_05.jpg
n735uf_06.jpg
n735uf_07.jpg
n735uf_08.jpg
n735uf_09.jpg
```

## WhatsApp Button

The WhatsApp floating button is **hidden** (`display:none`) and ready to activate.  
To enable: open `index.html`, find `.wa-btn{display:none;` and remove `display:none;`.

## Contact / Acquisition Lead

WhatsApp: +1 (808) 657-2700  
Waitlist form: https://form.typeform.com/to/uzFJYiFS

---

*Stratus Aviation — McAllen (KMFE) · Brownsville (KBRO) · Starbase*
