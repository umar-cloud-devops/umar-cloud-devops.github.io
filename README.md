# umar-cloud-devops.github.io

Personal portfolio of **Umar Mukthar N** — DevOps & Cloud Engineer.

**Live:** https://umar-cloud-devops.github.io

## Stack

Deliberately dependency-free: a single static `index.html` with inline CSS and vanilla JS.
No build step, no framework, no npm install — which is why it deploys anywhere in seconds
and loads fast.

- Animated node-network canvas background (respects `prefers-reduced-motion`)
- Typed role rotator and a scroll-triggered terminal boot sequence
- Scroll-triggered CI/CD pipeline visualisation
- Animated impact counters via `IntersectionObserver`
- Dark / light theme with `localStorage` persistence
- Fully responsive; accessible focus states

## Structure

```
index.html    # entire site (markup + styles + scripts)
assets/       # résumé PDF
.nojekyll     # serve files as-is, skip Jekyll processing
```

## Local preview

```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Deployment

Served by GitHub Pages from the `main` branch. Any push to `main` publishes.
