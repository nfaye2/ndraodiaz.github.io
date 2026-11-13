# Ndrao Faye — Academic Portfolio

Static site for [Ndrao Faye](https://orcid.org/0009-0002-1314-7418), Applied Linguist · Discourse Analyst · Multilingual Education Practitioner.

## Structure

```
site/
├── index.html          # Home
├── css/
│   └── style.css       # All styles — light/dark themes, responsive
├── data/               # Content source files — update these, not the HTML
│   ├── publications.json
│   ├── presentations.json
│   ├── teaching.json
│   ├── service.json
│   └── ai.json
├── pages/
│   ├── research.html
│   ├── publications.html
│   ├── presentations.html
│   ├── teaching.html
│   ├── service.html
│   └── cv.html
├── files/
│   └── FAYE_Ndrao_CV_Master.pdf   ← place CV PDF here
├── .nojekyll
└── README.md
```

## Deploying to GitHub Pages

1. Create a GitHub repository named `ndraodiaz.github.io` (or any repo name, then enable Pages in Settings → Pages).
2. Push the contents of this `site/` folder to the `main` branch root.
3. Place your CV PDF at `files/FAYE_Ndrao_CV_Master.pdf`.
4. GitHub Pages will serve `index.html` at your domain automatically.

## Custom domain (Netlify or GitHub Pages)

Add a `CNAME` file to the root with your domain, e.g.:
```
ndraodiaz.com
```

Then configure the DNS A records (GitHub Pages) or point your domain nameservers to Netlify.

## Updating content

- **Publication status changed?** Edit `data/publications.json`, then copy the updated entry into the matching section of `pages/publications.html`.
- **New presentation?** Add to `data/presentations.json` and to `pages/presentations.html`.
- **New CV version?** Replace `files/FAYE_Ndrao_CV_Master.pdf` and update the version date in `pages/cv.html`.

The data files are the record of truth. The HTML files render them. Keep both in sync.

## Last updated

November 2026
