# Website setup guide

This project now includes a lightweight static site in `site/` so you can publish documentation with GitHub Pages.

## 1) Local preview

From the repository root:

```bash
python -m http.server 8000
```

Then open:

- `http://localhost:8000/site/`

## 2) Customize content

Edit these files:

- `site/index.html` for page content and links.
- `site/styles.css` for branding, colors, and layout.

You can also add more pages under `site/` and link them from the homepage.

## 3) Publish with GitHub Pages

1. Push the branch to GitHub.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your branch and folder:
   - Branch: `main` (or your default branch)
   - Folder: `/site`
5. Save. GitHub will generate a public URL for your site.

## 3.5) Find your public URL

After GitHub Pages finishes deployment, your project URL will be:

- `https://<github-username>.github.io/<repository-name>/`

For this repository, if hosted under `rahamahals-create/AI-LibrariansGPT`, the URL should be:

- `https://rahamahals-create.github.io/AI-LibrariansGPT/`

If you configured a custom domain in Pages settings, use that domain instead.

## 4) Optional: custom domain

If you have a domain:

1. Add your domain in **Settings → Pages**.
2. Configure DNS records per GitHub docs.
3. Enable HTTPS after DNS is verified.

## 5) Suggested next enhancements

- Add a navigation bar with links to consultation and evaluation pages.
- Convert markdown docs to HTML pages for cleaner reading.
- Add an accessibility statement and contact handoff links.
- Add analytics only if it complies with your privacy policy.


## 6) URL troubleshooting

If GitHub says the site URL is invalid or unavailable, check:

1. **Repository name and case** must match exactly in the URL path (for example, `AI-LibrariansGPT` with exact capitalization).
2. **Pages source** must be set to your active branch (usually `main`) and folder **`/site`**.
3. Wait 1–5 minutes after saving Pages settings; first deployment can take longer.
4. Confirm the repository is public (or your plan supports private Pages).
5. Use the repository URL format (project site):
   - `https://<username>.github.io/<repository-name>/`
6. If using a custom domain, verify DNS first; otherwise use the default `github.io` URL.

For this project, the expected default URL is:

- `https://rahamahals-create.github.io/AI-LibrariansGPT/`
