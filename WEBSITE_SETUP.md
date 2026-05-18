# How to Create a Website URL for AI Librarian GPT

This repository now includes a static website (`index.html`) that can be published as a public URL. The simplest free option is GitHub Pages.

## Option 1: Publish with GitHub Pages

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, choose **GitHub Actions**.
5. Commit the included workflow in `.github/workflows/pages.yml`.
6. After the workflow finishes, your URL will usually be:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

For this repository name, it would look like:

```text
https://YOUR-GITHUB-USERNAME.github.io/Research-An-AI-Librarian---Resources---References---Consultations-/
```

## Option 2: Use a Custom Domain

1. Buy a domain from a registrar such as Namecheap, Google Domains/Squarespace Domains, GoDaddy, or Cloudflare.
2. In GitHub, go to **Settings** → **Pages** → **Custom domain**.
3. Enter the domain, for example:

```text
ailibrariangpt.com
```

4. Add the DNS records GitHub provides at your domain registrar.
5. Turn on **Enforce HTTPS** once GitHub confirms the domain.

## Important Note About the Chat Feature

The included website is a safe front-end starter. It creates a structured research prompt users can copy into an AI chat. To make it a live AI chat that responds directly on the website, add a backend service that calls an AI API.

Do **not** put private API keys inside `index.html`, because browser code is public. Use a backend such as:

- Node.js/Express on Render, Railway, Fly.io, or Vercel
- Python/FastAPI on Render, Railway, Fly.io, or Vercel
- A serverless function through Netlify, Vercel, or Cloudflare Workers

## Recommended Next Step

Publish the static site first with GitHub Pages. After the URL works, add a secure backend chat endpoint if you want the page to answer users directly instead of generating a prompt.
