# Onda Technologies Landing Page

Static marketing site for [Onda Technologies](https://www.ondatech.io/), deployed via GitHub Pages.

## Local preview

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Deploy (GitHub Pages)

1. Push to the `main` branch.
2. **Repository visibility:** GitHub Pages on private org repos requires a paid GitHub plan. For the free preview URL, either:
   - Make this repository **public** (recommended for a marketing site), or
   - Upgrade the org to GitHub Team / Enterprise.
3. In GitHub: **Settings → Pages → Build and deployment**.
4. Source: **Deploy from a branch**, branch **`main`**, folder **`/ (root)`**.
5. Site URL: **https://onda-technologies.github.io/landing/**

No build step required — plain HTML and CSS.

If Pages was not enabled automatically, an org admin must complete step 3 after step 2.

## Structure

```
index.html      # single-page site
styles.css      # styles
assets/         # favicon and future images
```

## Contact

[contact@ondatech.io](mailto:contact@ondatech.io)
