# Aia Nyll Capricho — Portfolio

Professional portfolio site for Aia Nyll Capricho — Virtual Assistant | Admin, Operations & Data Management.

A single-file, zero-dependency HTML/CSS site. No build step, no frameworks.

## Structure

- `index.html` — the entire site (styles embedded)
- `copy/portfolio-copy.md` — the full portfolio copy organized by section, with placeholders for content still to be gathered (screenshots, metrics, testimonials)

## Run locally

Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy free on GitHub Pages

1. Create a new repo on GitHub (e.g. `portfolio`), then from this folder:

   ```bash
   git remote add origin https://github.com/<your-username>/portfolio.git
   git push -u origin main
   ```

2. On GitHub: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**
3. Your site goes live at `https://<your-username>.github.io/portfolio/`

## To-do before calling it final

- [ ] Add 1–2 anonymized screenshots to the "Order Proofing & Tracking System" project
- [ ] Add a real metric (orders/week, error-rate improvement, response time)
- [ ] Request a short testimonial from the manager at Online Retail Services Ltd
- [ ] Verify phone number (+63 968 vs +63 956 — resume and old site disagree)
- [ ] Add a resume-download link (drop the PDF into the repo and link it from the hero)
